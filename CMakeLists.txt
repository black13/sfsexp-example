cmake_minimum_required(VERSION 3.5)
project(subprojects)

include_directories(sfsexpr)

# Add sub directories
add_subdirectory(sfsexpr)
add_subdirectory(example)