cmake_minimum_required(VERSION 3.8)
project(untitled4)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c test.h test.c vista/pila.h vista/pila.c)
add_executable(untitled4 ${SOURCE_FILES})