cmake_minimum_required(VERSION 3.14)
project(Incanabulum)

add_executable(incanabulum ./src/main.c)
target_compile_features(incanabulum PRIVATE c_std_90)
