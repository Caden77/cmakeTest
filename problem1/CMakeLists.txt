#Insert your code here :) (This is the way!)
cmake_minimum_required(VERSION 3.22)

project(CMakeProblem1)

include_directories(harp lib)

add_subdirectory(lib)
add_subdirectory(harp)

add_executable(perform.elf main.c)
target_link_libraries(perform.elf harplib)