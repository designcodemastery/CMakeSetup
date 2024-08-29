cmake_minimum_required(VERSION 3.5)
project(CMakeSetup
        VERSION 1.0.0
        DESCRIPTION "CMake Setup Test App"
        LANGUAGES CXX)

# List our source files
add_executable(CMakeSetup main.cpp source/Game.cpp)

target_compile_features(CMakeSetup PRIVATE cxx_std_20)

target_include_directories(CMakeSetup PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)
