cmake_minimum_required(VERSION 3.19)
set(PROJECT_NAME DotsTrieng)
project(${PROJECT_NAME})

set(CMAKE_CXX_STANDARD 20)

add_executable(${PROJECT_NAME} main.cpp)

find_package(glfw3 3.3 REQUIRED)
target_link_libraries(${PROJECT_NAME} glfw)


target_link_libraries(${PROJECT_NAME} /home/riki/Documents/Learn/LearnOpenGL/Libs/glad/libglad.a)