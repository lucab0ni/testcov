PROJECT(testcov)

cmake_minimum_required(VERSION 2.8)

SET(CMAKE_CXX_FLAGS
 "${CMAKE_CXX_FLAGS_DEBUG} -g -O0 -coverage")

include_directories(${PROJECT_SOURCE_DIR})
add_subdirectory(tests)

