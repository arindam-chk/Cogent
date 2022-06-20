project(Cogent)
cmake_minimum_required(VERSION 3.0)
enable_testing()


include_directories(src)

add_library(Cogent STATIC
    src/add.cc)
