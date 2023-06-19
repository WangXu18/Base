cmake_minimum_required(VERSION 3.24)
project(Base)

set(CMAKE_CXX_STANDARD 11)

set(SRC_LIST Base/strings/string_piece.cc)

include_directories(${CMAKE_SOURCE_DIR} Base
                                        Base/gen)

add_library(Base SHARED ${SRC_LIST})
