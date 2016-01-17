cmake_minimum_required(VERSION 3.3)
project(ccsrch)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    ccsrch.c
    ccsrch.h)

add_executable(ccsrch ${SOURCE_FILES})
