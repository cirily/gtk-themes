cmake_minimum_required(VERSION 3.5)
project(gtk-theme)
install(DIRECTORY Pisces DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Pisces-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Pisces-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
    
