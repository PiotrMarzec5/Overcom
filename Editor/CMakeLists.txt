cmake_minimum_required (VERSION 4.2)

set (CMAKE_CXX_STANDARD_REQUIRED ON)
set (CMAKE_CXX_STANDARD 23)
set (CMAKE_CXX_EXTENSIONS OFF)

project (OvercomEditor)

set (MainDir ../Main/Main.cpp)

add_executable (OvercomEditor ${MainDir})