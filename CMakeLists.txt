cmake_minimum_required(VERSION 3.8)
project(2017_ESGI_PROJECT_CIPHER)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c functions.c functions.h)
add_executable(2017_ESGI_PROJECT_CIPHER ${SOURCE_FILES})