cmake_minimum_required(VERSION 3.22)

project(ncurses-learning)

set(TARGET_NAME ncurses-app)

add_executable(${TARGET_NAME} ${CMAKE_SOURCE_DIR}/src/main.c)
