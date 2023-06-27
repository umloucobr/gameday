cmake_minimum_required (VERSION 3.8)

project ("gameday")

add_executable (gameday "gameday.cpp" "gameday.h")

set_property(TARGET gameday PROPERTY CXX_STANDARD 20)

