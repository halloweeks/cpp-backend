cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(backend VERSION 1.0)

include_directories(include)

add_executable(server src/server.cpp)
add_executable(client src/client.cpp)

target_link_libraries(server pthread mysqlclient)