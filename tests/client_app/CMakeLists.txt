project(client_app)
cmake_minimum_required(VERSION 3.0)

find_package(libappimage REQUIRED)

add_executable(client_app main.c)
target_link_libraries(client_app libappimage)
