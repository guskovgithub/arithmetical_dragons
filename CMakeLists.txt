cmake_minimum_required(VERSION 3.6)
project(arifmetical_dragons_vlad)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES arithmetical_dragons.cpp)
add_executable(arifmetical_dragons_vlad ${SOURCE_FILES})