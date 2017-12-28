file (GLOB_RECURSE SOURCES src/*.c)

add_executable (zipident ${SOURCES})

target_link_libraries (zipident LINK_PUBLIC datlib m ${ZLIB_LIBRARIES})
