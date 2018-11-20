cmake_minimum_required(VERSION 3.12)
project(glew)

execute_process(COMMAND "make" WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/auto)

add_subdirectory(build/cmake)