cmake_minimum_required(VERSION 3.13)
project(Etap2)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17 -pthread -lncurses")

add_executable(Etap2 main.cpp)
target_link_libraries(Etap2 "-lncurses")