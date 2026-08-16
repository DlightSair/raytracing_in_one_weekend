cmake_minimum_required(VERSION 3.10)

project(Test)

add_executable(Test src/main.cpp)

target_include_directories(Test PRIVATE "headers")