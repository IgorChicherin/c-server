cmake_minimum_required(VERSION 3.5)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

set(project_name miniserver)
project(${project_name} C)

set(SOURCES src/app.c)
set(HEADERS src/app.h)

add_executable(${project_name} ${SOURCES} ${HEADERS})
