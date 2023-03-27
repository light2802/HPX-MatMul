cmake_minimum_required(VERSION 3.25)

project(Paralle_Matrix_Multiplication)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++20")

add_subdirectory(lib)

enable_testing()
include(CTest)
add_subdirectory(tests)

add_test(unit  tests/test1)
