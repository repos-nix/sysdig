include_directories(${PROJECT_SOURCE_DIR}/common)
include_directories(${PROJECT_SOURCE_DIR}/userspace/libscap)

add_executable(scap-validatebuffer
	test.c)

target_link_libraries(scap-validatebuffer
	scap)
