cmake_minimum_required(VERSION 2.8)
message("========")
set(PROJECT_NAME "test")
project(${PROJECT_NAME})
set(SOURCES src/main.cpp)

message("========")
message("========")

add_executable(${PROJECT_NAME} ${SOURCES})
