cmake_minimum_required(VERSION 3.12)
project(jarvis)

add_executable(${PROJECT_NAME} helloo.cpp)

target_link_libraries(${PROJECT_NAME} mylib)

add_subdirectory(lib)
