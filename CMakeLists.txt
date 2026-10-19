cmake_minimum_required(VERSION 4.1)
project(untitled100 CUDA)

set(CMAKE_CUDA_STANDARD 20)

add_executable(untitled100 main.cu)

set_target_properties(untitled100 PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
