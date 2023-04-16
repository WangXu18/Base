cmake_minimum_required(VERSION 3.25)
project(Base)

set(CMAKE_CXX_STANDARD 17)

include_directories(${CMAKE_SOURCE_DIR})

add_library(Base SHARED base/library.cpp)
