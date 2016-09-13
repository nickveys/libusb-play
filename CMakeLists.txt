cmake_minimum_required (VERSION 3.6)
project (libusb-play)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/cmake/Modules/")

find_package(libusb-1.0 REQUIRED)

add_subdirectory (lsusb)
