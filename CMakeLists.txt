cmake_minimum_required(VERSION 3.19)
project(pi_digits C)

set(CMAKE_C_STANDARD 99)

add_executable(pi_digits main.c)
target_link_libraries(
        pi_digits
        m
        gmp
)