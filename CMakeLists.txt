cmake_minimum_required(VERSION 3.8)

project(GTL)

file (GLOB_RECURSE SOURCES
    src/*.cpp
)

add_executable(gtl_test main.cpp ${SOURCES})
target_include_directories(gtl_test PUBLIC ./include)
