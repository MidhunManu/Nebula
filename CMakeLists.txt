cmake_minimum_required(VERSION 3.20)
project(Nebula VERSION 1.0 LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED on)

add_executable(nebula
    src/main.cpp
)

