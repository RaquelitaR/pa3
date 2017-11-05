cmake_minimum_required(VERSION 3.8)
project(pa3)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        src/http_get.c
        src/http_get.h
        src/http_head.c
        src/http_head.h
        src/http_post.c
        src/http_post.h
        src/http_server.c
        src/http_server.h
        src/http_spec.h
        src/main.c)

add_executable(pa3 ${SOURCE_FILES})