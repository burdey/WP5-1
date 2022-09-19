cmake_minimum_required(VERSION 3.22)
project(WP5)

set(CMAKE_CXX_STANDARD 14)

add_executable(WP5 main.cpp MapGeneric.h MapGeneric.cpp FilterGeneric.h FilterGeneric.cpp ReduceGeneric.h ReduceGeneric.cpp)
