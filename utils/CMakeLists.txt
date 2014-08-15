include_directories(./)
add_library(utils movement.cpp stat.cpp)
message("msg" ${LIB_INSTALL_DIR})
install(TARGETS utils ARCHIVE DESTINATION ${LIB_INSTALL_DIR})
