cmake_minimum_required(VERSION 3.13)
project(COMP9024_19T2)

set(CMAKE_CXX_STANDARD 14)

# include_directories(Pre_Class)

add_executable(COMP9024_19T2
        Assignments_Class/version02/boardADT.c
        Assignments_Class/version02/boardADT.h
        Assignments_Class/version02/puzzle.c)
