file (GLOB_RECURSE SOURCES src/*.c)

add_executable (datutil ${SOURCES})

target_link_libraries (datutil LINK_PUBLIC datlib m ${ZLIB_LIBRARIES})
