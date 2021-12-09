cmake_minimum_required(VERSION 3.15.0 FATAL_ERROR)

set(target_name example)

file(GLOB SRC_FILE * *.h *.hpp *.cpp)

#add_executable(${target_name} ${SRC_FILE})
add_executable(${target_name} rtsp_h264_file.cpp)

target_include_directories(${target_name} PRIVATE ../src)

target_link_libraries(${target_name} PRIVATE net xop)
