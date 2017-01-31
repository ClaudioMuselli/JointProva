cmake_minimum_required(VERSION 2.6)
project(joint)

add_executable(joint main.cpp)

install(TARGETS joint RUNTIME DESTINATION bin)
