cmake_minimum_required(VERSION 3.14 FATAL_ERROR)

project(fun_cpp)


# ---- Executable ----

add_executable(fun source/main.cpp)
target_compile_features(fun PUBLIC cxx_std_20)

