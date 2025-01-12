cmake_minimum_required(VERSION 3.5.0)
project(raytracer VERSION 0.1.0 LANGUAGES C CXX)

# Add the executable
add_executable(raytracer main.cpp)

# Specify the C++ standard version
target_compile_features(raytracer PRIVATE cxx_std_17)