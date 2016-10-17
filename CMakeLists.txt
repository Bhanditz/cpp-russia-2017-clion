cmake_minimum_required(VERSION 3.6)
project(arkan9)

set(CMAKE_CXX_STANDARD 11)

find_package(Qt5Widgets REQUIRED)

set(SOURCE_FILES main.cpp)
add_executable(arkan9 ${SOURCE_FILES})
target_link_libraries(arkan9 Qt5::Widgets)