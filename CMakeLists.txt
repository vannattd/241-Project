cmake_minimum_required(VERSION 3.14)
project(241_Project C)

set(CMAKE_C_STANDARD 99)

add_executable(241_Project main.c)
target_link_libraries(241_Project m)