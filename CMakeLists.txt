cmake_minimum_required(VERSION 3.20)
project(home C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(home
        dcel.c
        dcel.h
        gtk.c
        gtk.h
        output.c
        output.h
        problem.c
        problem.h
        readData.c
        readData.h
        voronoi2.c
        watchtowerStruct.c
        watchtowerStruct.h)
