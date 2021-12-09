cmake_minimum_required(VERSION 3.15.0 FATAL_ERROR)

set(CMAKE_CXX_STANDARD 17)

project(RtspServer VERSION 0.1.0 LANGUAGES CXX C)

add_subdirectory(src)
add_subdirectory(example)
