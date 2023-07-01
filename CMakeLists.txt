cmake_minimum_required(VERSION 3.13)
project(log.c)

add_library(log.c STATIC "src/log.h" "src/log.c")