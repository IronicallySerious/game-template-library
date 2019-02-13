cmake_minimum_required(VERSION 3.8)

project(GTL)

add_executable(gtl_test
	src/gtl.cpp
	main.cpp
)

target_include_directories(gtl_test PUBLIC ./include)
