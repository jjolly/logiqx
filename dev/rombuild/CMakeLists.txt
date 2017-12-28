file (GLOB_RECURSE SOURCES src/*.c)

add_executable (rombuild ${SOURCES})

target_link_libraries (rombuild LINK_PUBLIC datlib m ${ZLIB_LIBRARIES})
