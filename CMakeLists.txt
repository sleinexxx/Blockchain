cmake_minimum_required(VERSION 3.5.1)

set(PROJECT_NAME Blockchain)
project(${PROJECT_NAME})

include_directories(include)

add_executable(${PROJECT_NAME} main.cpp)
