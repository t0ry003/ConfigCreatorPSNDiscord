cmake_minimum_required(VERSION 3.19)
project(ConfigCreatorPSNDiscord)

set(CMAKE_CXX_STANDARD 14)

set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -static-libstdc++ -static-libgcc")
add_executable(ConfigCreatorPSNDiscord main.cpp)