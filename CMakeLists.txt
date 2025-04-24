cmake_minimum_required(VERSION 3.27)
project(games101)

find_package(Eigen3 REQUIRED)

set(CMAKE_CXX_STANDARD 23)

add_executable(games101 main.cpp)

target_link_libraries(games101 PRIVATE Eigen3::Eigen)