cmake_minimum_required(VERSION 3.0)

set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")

project(rule_of_5)

add_executable(
	rule_of_5
	rule_of_five_example.cpp
	
)
