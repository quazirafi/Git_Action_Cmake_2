cmake_minimum_required(VERSION 3.10)

# set the project name
project(Git_Action_Cmake_2)

# add the executable
add_executable(Git_Action_Cmake_2 test.cpp)

target_include_directories(Git_Action_Cmake_2 PUBLIC "${PROJECT_BINARY_DIR}")
