
add_executable(3dvgl main.cpp scene.cpp screenshot.cpp)
target_link_libraries(3dvgl nvstusb ${OPENGL_LIBRARIES} ${GLUT_LIBRARIES})