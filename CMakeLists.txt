cmake_minimum_required(VERSION 4.0) # CMake Version Number

project(alibi) # "Project" name - [TODO-Javier]: what is a "project"?

add_executable(myprogram src/Alibi.cc) # (executable name, source file to build)

# cmake -G "MinGW Makefiles" -B build in the parent dir (C:\Users\javie\Projects\alibi)