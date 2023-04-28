cmake_minimum_required(VERSION 3.24)
project(test_base)

set(CMAKE_CXX_STANDARD 17)

set(SRC_LISTS
        main.cpp)

add_executable(${PROJECT_NAME} ${SRC_LISTS})