cmake_minimum_required(VERSION 3.22)
project(a2)

set(CMAKE_CXX_STANDARD 14)

add_executable(a2
        baseline.cpp
        compute_stats.cpp)
