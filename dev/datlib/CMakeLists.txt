cmake_minimum_required (VERSION 3.5)
project (Logiqx)

file (GLOB_RECURSE DATLIB_SOURCES LIST_DIRECTORIES false src/*.c)

add_library (datlib ${DATLIB_SOURCES})
