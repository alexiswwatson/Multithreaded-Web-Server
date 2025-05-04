cmake_minimum_required(VERSION 3.20)
project(multithreaded-web-server C)

set(CMAKE_C_STANDARD 11)

add_executable(server src/wserver.c src/io_helper.c src/request.c)
add_executable(client src/wclient.c src/io_helper.c src/request.c)

