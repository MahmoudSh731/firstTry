cmake_minimum_required(VERSION 3.15)
project(gitfirstTry C)

set(CMAKE_C_STANDARD 99)

add_executable(gitfirstTry main.c list.h)
target_link_libraries(gitfirstTry ${CMAKE_SOURCE_DIR}/libmtm.a)