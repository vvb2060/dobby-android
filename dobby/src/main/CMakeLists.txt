cmake_minimum_required(VERSION 3.5)
project(Dobby)

find_package(cxx REQUIRED CONFIG)
link_libraries(cxx::cxx)

add_subdirectory(dobby)
