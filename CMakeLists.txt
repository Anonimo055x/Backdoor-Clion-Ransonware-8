cmake_minimum_required(VERSION 3.23)
project(Block)

set(CMAKE_CXX_STANDARD 23)

add_executable(Block main.cpp var.h object.h internal.h import.h string.h Program.h Ransonware.cpp Wordlist.h)
