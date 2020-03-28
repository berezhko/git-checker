cmake_minimum_required(VERSION 3.5)

project(git-checker LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories( ./libs )

add_subdirectory(libs)

add_executable(git-checker main.cpp)

target_link_libraries(git-checker libs)
