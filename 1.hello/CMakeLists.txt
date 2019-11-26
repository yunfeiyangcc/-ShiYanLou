cmake_minimum_required(VERSION 3.5)

project(hello)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++0x")

add_executable(hello hello.cpp)