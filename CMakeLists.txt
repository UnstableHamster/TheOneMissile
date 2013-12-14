cmake_minimum_required(VERSION 2.8)
project(TheOneMissile)

list(APPEND CMAKE_MODULE_PATH "./cmake/")
include(FindSDL2)

if(NOT SDL2_FOUND)
  message(FATAL_ERROR "Please install the SDL2 library.")
endif(NOT SDL2_FOUND)

add_subdirectory(src)
