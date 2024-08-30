cmake_minimum_required(VERSION 3.30)

add_compile_options(-Wall -Wextra -Wpedantic)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

set(SOURCE_FILES main.cpp)
set(PROJECT_NAME RegexEngine)

project(${PROJECT_NAME})
add_executable(${PROJECT_NAME} ${SOURCE_FILES})
