cmake_minimum_required(VERSION 3.5)
project(CMakeSetup
        VERSION 1.0.0
        DESCRIPTION "CMake Setup Test App"
        LANGUAGES CXX)

add_executable(CMakeSetup main.cpp)
target_compile_features(CMakeSetup PRIVATE cxx_std_20)
