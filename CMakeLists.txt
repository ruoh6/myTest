cmake_minimum_required(VERSION 3.23)
project(myTest)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(myTest main.cpp
        Test.cpp
        Test.h)
