cmake_minimum_required(VERSION 3.13.4)

project(testing-test)

add_executable($(PROJECT_NAME) testing.cpp)

# This builder is better that make.
