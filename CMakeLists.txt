cmake_minimum_required(VERSION 3.5)

project(OrionEditor
        LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)

add_executable(OrionEditor ${OrionEditor_SOURCES})

add_subdirectory(src)
