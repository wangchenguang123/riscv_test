cmake_minimum_required(VERSION 3.16)
project(riscv_test)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 17)

# 添加源文件
add_executable(riscv_test hello.cpp)
