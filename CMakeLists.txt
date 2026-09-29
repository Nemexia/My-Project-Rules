cmake_minimum_required(VERSION 4.3)
project(MyProject
        VERSION 0.1.0
        DESCRIPTION "MyProject Description"
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_ASM_EXTENSIONS OFF)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(MyProject
        src/main.cpp)

find_package(raylib CONFIG REQUIRED)

target_link_libraries(MyProject PRIVATE raylib)