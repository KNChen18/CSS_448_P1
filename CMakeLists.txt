cmake_minimum_required(VERSION 3.21)
project(CSS_448_P1 C)

set(CMAKE_C_STANDARD 11)

include_directories("Source Code")

add_executable(CSS_448_P1
        "Source Code/lex.c"
        "Source Code/lex.h"
        "Source Code/main.c"
        "Source Code/main.h"
        "Source Code/tok.c"
        "Source Code/tok.h"
        "Source Code/toks.c"
        "Source Code/toks.h"
        "Source Code/ut.c"
        "Source Code/ut.h")
