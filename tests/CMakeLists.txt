add_executable(test1 test1.cpp)
target_link_libraries(test1 matrix)
include_directories(${CMAKE_SOURCE_DIR}/lib)
