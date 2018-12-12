cmake_minimum_required(VERSION 2.7)
project(Raytracer)

file(GLOB_RECURSE SOURCES src/*.cpp)

add_executable(Raytracer ${SOURCES})
target_include_directories(Raytracer PRIVATE include/)