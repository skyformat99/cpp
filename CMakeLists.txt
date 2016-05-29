cmake_minimum_required(VERSION 2.8.0)
project(examples)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_subdirectory(pty)
add_subdirectory(logger)
