cmake_minimum_required(VERSION 3.10)
project(milner VERSION 0.1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

file(GLOB_RECURSIVE_SOURCES "src/*.cpp")

add_executable(milner ${SOURCES})

target_included_directories(milner PRIVATE src)
