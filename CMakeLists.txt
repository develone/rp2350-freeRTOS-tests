cmake_minimum_required(VERSION 3.12)

include(pico_sdk_import.cmake)

project(Pico-FreeRTOS)

pico_sdk_init()
add_subdirectory(pico-littlefs)
add_subdirectory(lifting)
add_subdirectory(cir-buf)
add_subdirectory(crc_crc16)
add_subdirectory(xmodem)
add_subdirectory(klt)
add_subdirectory(openjpeg)
add_subdirectory(freertos-RPi)
