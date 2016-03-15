
add_library(nvstusb nvstusb.c usb_libusb.c)
target_link_libraries(nvstusb ${LIBUSB_1_LIBRARIES})