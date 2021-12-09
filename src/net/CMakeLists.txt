cmake_minimum_required(VERSION 3.15.0 FATAL_ERROR)

set(target_name net)

file(GLOB SRC_FILE * *.h *.hpp *.cpp)

add_library(${target_name} STATIC ${SRC_FILE})
