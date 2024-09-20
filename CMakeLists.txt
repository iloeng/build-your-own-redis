cmake_minimum_required(VERSION 3.29)
project(build_your_own_redis C)

set(CMAKE_C_STANDARD 11)

add_executable(build_your_own_redis chap03/server.c
        chap03/client.c)
