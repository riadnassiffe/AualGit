cmake_minimum_required(VERSION 3.15)
project(jogo)

find_package(raylib REQUIRED)

add_library(raygui SHARED IMPORTED)
set_property(TARGET raygui PROPERTY IMPORTED_LOCATION "include/raygui.so")

add_executable(${PROJECT_NAME} src/main.c  )
target_link_libraries(${PROJECT_NAME} PRIVATE raylib)

a sd,fnasdkfasdfasfASdFaSdFasDf ASF adfas
dfa sdfasd fa


asd fasd fas
