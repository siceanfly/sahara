cmake_minimum_required(VERSION 3.28)
project(sahara)

set(CMAKE_CXX_STANDARD 20)

add_executable(sahara main.cpp
        src/common/DataTypes.h
        src/common/Fault.h
        src/common/Fault.cpp)
