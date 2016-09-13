add_executable(lsusb main.c)

include_directories(${LIBUSB_1_INCLUDE_DIRS})

target_link_libraries(lsusb ${LIBUSB_1_LIBRARIES})
