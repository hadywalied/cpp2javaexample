cmake_minimum_required(VERSION 3.17)
project(cpp2javaexample)

set(CMAKE_CXX_STANDARD 11)

find_package(JNI REQUIRED)
INCLUDE_DIRECTORIES(${JNI_INCLUDE_DIRS})

add_executable(cpp2javaexample main.cpp)

target_link_libraries(cpp2javaexample "C:/Program Files/Java/jdk-16.0.2/lib/jvm.lib")



