cmake_minimum_required(VERSION 3.21)

add_executable("32_Homework_3" main.cpp function.cpp ${MY_INCLUDE_DIR}/function.h ${MY_INCLUDE_DIR}/google)
target_include_directories("32_Homework_3" PUBLIC ${MY_INCLUDE_DIR})