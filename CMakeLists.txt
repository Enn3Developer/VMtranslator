cmake_minimum_required(VERSION 3.27)
project(VMtranslator C)

set(CMAKE_C_STANDARD 11)

add_executable(VMtranslator file.h file.c string.h string.c
        main.c)
