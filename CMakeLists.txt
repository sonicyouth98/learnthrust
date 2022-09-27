cmake_minimum_required(VERSION 3.22)
project(learnthrust)

set(CMAKE_CXX_STANDARD 23)

file(GLOB_RECURSE source CONFIGURE_DEPENDS include/*.h src/*.cpp)


