cmake_minimum_required(VERSION 3.0)
project(ada_renderer)

set(CMAKE_CXX_STANDARD 17)

add_executable(ada_renderer main.cpp
        tgaimage.cpp)
