cmake_minimum_required(VERSION 3.26)
project(cmake_error_test)

set(CMAKE_CXX_STANDARD 20)

find_package(Threads)

add_executable(cmake_error_test main.cpp)
