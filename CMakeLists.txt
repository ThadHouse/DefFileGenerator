cmake_minimum_required (VERSION 2.6)
project (DefFileGenerator)

file(GLOB_RECURSE SRC_FILES src/*.cpp)
include_directories(include src)
add_executable(DefFileGenerator ${SRC_FILES})