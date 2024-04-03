cmake_minimum_required(VERSION 3.9)
project(pinnedVector VERSION 1.3.1)

add_library(pinnedVector INTERFACE)
target_include_directories(pinnedVector INTERFACE include "${CMAKE_CURRENT_SOURCE_DIR}/")
