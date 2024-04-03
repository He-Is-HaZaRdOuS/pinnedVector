cmake_minimum_required(VERSION 3.9)
project(pinnedVector)

add_library(pinnedVector INTERFACE)
target_include_directories(pinnedVector INTERFACE include "${CMAKE_CURRENT_SOURCE_DIR}/")
