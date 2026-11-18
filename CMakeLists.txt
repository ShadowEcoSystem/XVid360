cmake_minimum_required(VERSION 3.25)
project(XVid360 C)

add_executable(XVid360 main.c)
set_target_properties(XVid360 PROPERTIES C_STANDARD 17 C_EXTENSIONS ON)
target_compile_options(XVid360 PRIVATE -Wall -Wextra -Werror)

xsdk_add_xex(XVid360)
