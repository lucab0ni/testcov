PROJECT(testcov)


SET(CMAKE_CXX_FLAGS
 "${CMAKE_CXX_FLAGS_DEBUG} -g -O0 -coverage")

add_executable(prog1 prog1)
