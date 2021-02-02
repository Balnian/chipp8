cmake_minimum_required(VERSION 3.16)

project(
    "Chipp8"
    VERSION 0.1.0
    LANGUAGES CXX
)


include_directories(include)

add_executable(${PROJECT_NAME}
    "src/main.cpp")