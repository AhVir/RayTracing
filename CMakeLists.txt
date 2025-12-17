cmake_minimum_required(VERSION 3.10)

# Name of your project
project(RayTracer)

# Set the C++ standard to C++11 or higher (Ray Tracing in One Weekend usually needs C++11)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Define the executable name and the source file
add_executable(inOneWeekend main.cc)
