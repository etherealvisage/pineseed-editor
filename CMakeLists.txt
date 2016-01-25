cmake_minimum_required(VERSION 2.6)

cmake_policy(SET CMP0012 NEW)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_LIST_DIR})

project(pineseed-editor C CXX)

add_subdirectory(src)
