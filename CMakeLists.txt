cmake_minimum_required(VERSION 3.28)

project(MyLib)

add_library(MyLib)
target_sources(MyLib PRIVATE "Include/MyLib.h" "Source/MyLib.cpp")
target_include_directories(MyLib PUBLIC "Include")

install(TARGETS MyLib)
