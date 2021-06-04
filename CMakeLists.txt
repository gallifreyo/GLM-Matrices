cmake_minimum_required(VERSION 3.12)

project(Matrices)

add_executable(Matrices main.cpp)

target_include_directories(Matrices PRIVATE deps/glm)
