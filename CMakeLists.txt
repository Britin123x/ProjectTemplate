cmake_minimum_required(VERSION 3.10)

project(Template)


set(CMAKE_C_STANDARD 23)
set(CMAKE_C_STANDARD_REQUIRED False)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIRECTORY}/bin/")


add_subdirectory("src")
add_subdirectory("lib")
add_subdirectory("include")
add_subdirectory("tests")
add_subdirectory("scripts")
add_subdirectory("bin")