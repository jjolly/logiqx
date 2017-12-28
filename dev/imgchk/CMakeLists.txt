file (GLOB_RECURSE SOURCES src/*.c)

add_executable (imgchk ${SOURCES})

target_link_libraries (imgchk LINK_PUBLIC datlib m ${ZLIB_LIBRARIES})
