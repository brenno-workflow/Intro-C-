cmake_minimum_required(VERSION 3.20)

project(HelloWorld)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(HelloWorld
    src/main.cpp
    src/utils.cpp
)