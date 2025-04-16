cmake_minimum_required(VERSION 3.0)

project(super2esc)

add_executable(super2esc super2esc.c)
target_compile_options(super2esc PRIVATE -Wall -Wextra)

install(TARGETS super2esc RUNTIME DESTINATION bin)
