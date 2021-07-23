cmake_minimum_required(VERSION 3.0.0)

project(Hello_World VERSION 1.0.0)

add_subdirectory(libraries)

add_executable(hello_world main.cpp)

target_link_libraries(hello_world my_math)
