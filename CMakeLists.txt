cmake_minimum_required(VERSION 2.6)

project(HelloDX12)

include_directories($ENV{INCLUDE})
link_directories($ENV{LIB})

add_definitions(-DUNICODE -D_UNICODE)

add_subdirectory(src)