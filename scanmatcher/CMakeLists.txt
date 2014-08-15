add_library(gmapping_scanmatcher eig3.cpp scanmatcher.cpp scanmatcherprocessor.cpp smmap.cpp)
target_link_libraries(gmapping_scanmatcher gmapping_sensor_range gmapping_utils)

install(TARGETS gmapping_scanmatcher DESTINATION ${LIB_INSTALL_DIR})
