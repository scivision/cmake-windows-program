cmake_minimum_required(VERSION 3.15...3.22)
project(ForestFirst LANGUAGES CXX)

# https://rosettacode.org/wiki/Forest_fire#C.2B.2B
add_executable(forest_fire WIN32 forest_fire.cpp)
# WIN32 enables target property WIN32_EXECUTABLE that adds per-compiler linker flags

# depending on the Windows C++ coding style, you may need additional compiler dependent flags like:
#   -municode  for _tWinMain
