cmake_minimum_required(VERSION 3.6)

project(demo)

set(CURRENT_DIR ${CMAKE_CURRENT_SOURCE_DIR})

set(NET_INCLUDE_DIR ${CURRENT_DIR}/../net/include)
set(NET_LIB_DIR ${CURRENT_DIR}/../net/lib)

include_directories(${NET_INCLUDE_DIR})
library_directories(${NET_LIB_DIR})