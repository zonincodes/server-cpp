cmake_minimum_required(VERSION 3.0)
project(SRC)

add_library(${PROJECT_NAME} server.cpp server.h)
target_include_directories(${PROJECT_NAME} PUBLIC include/)