cmake_minimum_required(VERSION 3.22)

project(ncurses-learning)

set(TARGET_NAME ncurses-app)

add_executable(${TARGET_NAME} ${CMAKE_SOURCE_DIR}/src/main.c)
target_include_directories(${TARGET_NAME} PRIVATE "${CMAKE_SOURCE_DIR}/inc")

target_link_libraries(${TARGET_NAME} PRIVATE ncurses)
