cmake_minimum_required(VERSION 3.26)
project(C_BasicMenu C)

set(CMAKE_C_STANDARD 11)


link_directories(./libs)

link_libraries(libC_LibMenu.a)


add_executable(C_BasicMenu
        library.h
        main.c
)




