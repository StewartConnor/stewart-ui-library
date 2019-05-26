# CMakeList.txt : CMake project for UI-Library, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project(UI-Library)

# Add source to this project's executable.
add_library (UI-Library "UI-Library.cpp" "UI-Library.h")

target_include_directories (UI-Library PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})