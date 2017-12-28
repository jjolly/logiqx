find_package (ZLIB)

add_subdirectory("datlib")
add_subdirectory("datutil")
add_subdirectory("imgchk")
add_subdirectory("mamediff")
add_subdirectory("rombuild")
add_subdirectory("rominfo")
add_subdirectory("zipident")

target_include_directories (datlib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
