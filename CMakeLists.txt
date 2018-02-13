cmake_minimum_required(VERSION 3.8)
project(Project3)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        CMakeLists.txt
        main.cpp
        Makefile
        Project3.cpp
        String.h)

add_executable(Project3 ${SOURCE_FILES})