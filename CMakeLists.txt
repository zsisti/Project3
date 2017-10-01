cmake_minimum_required(VERSION 3.8)
project(Project3)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        .idea/misc.xml
        .idea/modules.xml
        .idea/Project3.iml
        .idea/vcs.xml
        .idea/workspace.xml
        main.cpp
        Makefile
        Project3.cpp
        README.md
        String.h)

add_executable(Project3 ${SOURCE_FILES})