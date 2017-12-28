file (GLOB_RECURSE SOURCES src/*.c)

add_executable (rominfo ${SOURCES})

target_link_libraries (rominfo LINK_PUBLIC datlib m ${ZLIB_LIBRARIES})
