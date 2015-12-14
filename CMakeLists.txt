cmake_minimum_required(VERSION 3.4)

project(emulator)

add_definitions(-std=c++11 -Wall -Werror -Wextra -pedantic -g -ferror-limit=10000)

add_executable(emulator src/main.cc src/CPU.cc src/CPU.h src/Gameboy.cc src/Gameboy.h src/MMU.cc src/MMU.h src/Clock.cc src/Clock.h src/Memory.cc src/Memory.h)