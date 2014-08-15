include_directories(./)
add_library(gmapping_utils movement.cpp stat.cpp)
install(TARGETS gmapping_utils ARCHIVE DESTINATION ${LIB_INSTALL_DIR})
