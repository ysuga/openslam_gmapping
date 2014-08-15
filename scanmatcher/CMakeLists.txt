add_library(scanmatcher eig3.cpp scanmatcher.cpp scanmatcherprocessor.cpp smmap.cpp)
target_link_libraries(scanmatcher sensor_range utils)

install(TARGETS scanmatcher DESTINATION ${LIB_INSTALL_DIR})
