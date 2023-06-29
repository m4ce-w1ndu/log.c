cmake_minimum_required(VERSION 3.8)
project(log.c)

add_library(${CMAKE_PROJECT_NAME} STATIC "src/log.h" "src/log.c")