cmake_minimum_required(VERSION 3.4)

project(formatter_ex)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(formatter_ex STATIC ${CMAKE_CURRENT_SOURCE_DIR}/formatter_ex.cpp)

include_directories(  /home/runner/work/lab04/lab04/formatter_ex_lib   /home/runner/work/lab04/lab04/formatter_lib )
