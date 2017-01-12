cmake_minimum_required(VERSION 3.2.2)

project(travis-test)

include (GNUInstallDirs)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=c++11")
file (GLOB SOURCES *.cpp)

add_executable(travis-test ${SOURCES})
