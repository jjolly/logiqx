file (GLOB_RECURSE SOURCES src/*.c)

add_executable (mamediff ${SOURCES})

target_link_libraries (mamediff LINK_PUBLIC datlib m ${ZLIB_LIBRARIES})
