cmake_minimum_required(VERSION 3.16)

project(linkedlist_reverse LANGUAGES C)

add_executable(linkedlist_reverse main.c)

include(GNUInstallDirs)
install(TARGETS linkedlist_reverse
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
