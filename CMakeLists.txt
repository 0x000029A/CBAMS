cmake_minimum_required(VERSION 3.22)
project(CBAMS C)

set(CMAKE_C_STANDARD 11)

add_executable(CBAMS
        main.c Array_ADT.c Array_ADT.h CBAMS.c CBAMS.h)
