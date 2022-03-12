cmake_minimum_required(VERSION 3.12)
  
add_definitions(-DMAX)
project(TEL LANGUAGES CXX)
set(SOURCES test.cpp)

set(CMAKE_CXX_STANDARD 17)
message(STATUS "CMAKE_CXX_STANDARD: ${CMAKE_CXX_STANDARD}")
add_executable(test ${SOURCES})
