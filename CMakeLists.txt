cmake_minimum_required(VERSION 2.8.11)
project(ConanWrapper CXX)

message(STATUS "Conan CMake Wrapper")
include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup(TARGETS)

add_subdirectory(sources)