cmake_minimum_required(VERSION 4.0)
project(RouterToReq)

set(CMAKE_CXX_STANDARD 17)

add_executable(RouterToReq main.cpp
        zhelpers.h)

target_link_libraries(RouterToReq zmq)

