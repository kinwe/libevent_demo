cmake_minimum_required(VERSION 3.17)
project(untitled2)


include_directories(/usr/local/Cellar/libevent/2.1.11_1/include)
link_directories(/usr/local/Cellar/libevent/2.1.11_1/lib)
set(CMAKE_CXX_STANDARD 14)

add_executable(untitled2 main.cpp)
target_link_libraries(untitled2 event pthread)