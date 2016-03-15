set(CMAKE_MODULE_PATH ${PROJECT_SOURCE_DIR})
find_package(OpenGL REQUIRED)
find_package(GLUT REQUIRED)
find_package(USB REQUIRED)

include_directories(${OPENGL_INCLUDE_DIR})
include_directories(${GLUT_INCLUDE_DIR})
include_directories(${LIBUSB_1_INCLUDE_DIRS})
include_directories(lib)

add_subdirectory(lib)
add_subdirectory(src)