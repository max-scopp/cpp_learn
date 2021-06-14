cmake_minimum_required(VERSION 3.16)
project(first_project VERSION 0.0.1.0)

set(CMAKE_CXX_STANDARD 17) # -std=c++17

# creates an json with all compile commands inside
set(CMAKE_EXPORT_COMPILE_COMMANDS ON) # important

add_subdirectory(hello_world)