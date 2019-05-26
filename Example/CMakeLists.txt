# CMakeList.txt : CMake project for UI-Library, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project(UI-Library-Example)

# Add source to this project's executable.
add_executable (UI-Library-Example "Example.cpp" "Example.h")

target_link_libraries(UI-Library-Example LINK_PUBLIC UI-Library)

# TODO: Add tests and install targets if needed.
