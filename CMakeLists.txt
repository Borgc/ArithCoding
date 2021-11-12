cmake_minimum_required(VERSION 3.17)
project(untitled2)

set(CMAKE_CXX_STANDARD 14)

add_library( compress.cpp compress.h decode.h decode.cpp encode.h encode.cpp )
add_executable(main main.cpp compress.cpp decode.cpp encode.cpp)