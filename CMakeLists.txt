cmake_minimum_required(VERSION 3.8)
project(2048)

include_directories(include)
file(GLOB_RECURSE SOURCES src/*.c)

add_executable(2048 ${SOURCES})
