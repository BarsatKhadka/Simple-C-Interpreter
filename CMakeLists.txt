cmake_minimum_required(VERSION 3.30)
project(Simple_C_Interpreter C)

set(CMAKE_C_STANDARD 11)

add_executable(Simple_C_Interpreter main.c
        common.h)
