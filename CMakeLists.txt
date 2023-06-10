cmake_minimum_required(VERSION 3.26.4)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(SDL)

target_include_directories(${PROJECT_NAME} PRIVATE ./include)

