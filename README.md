# Raylib-linux-template

This repository serves as a simple template for the raylib graphics library.
The primary goal of this template is to be self contained, meaning that the
number of external dependencies for compilation has been minizmized.

The example program is written in c & includes a single source file and a simple makefile that
compiles & links statically to the raylib library.

## Raylib Library

This repository contains the required header & object file(s) needed
to compile your program with raylib. Raylib provides an easy way to 
incorporate graphics, sound, and user input into your programs.

*Files included from raylib v5.0 release*
Source Repository: https://github.com/raysan5/raylib

## Install OpenGL

Raylib requires the opengl library to link properly

To install on linux: `sudo apt-get install mesa-utils freeglut3-dev`

*The CS1 machines already have this library installed

## Compiling

To compile the program: `make`

Then, to run the program: `./program`

If you wish to compile & then immediately run your program: `make run`

To clean up the workspace (objects & binary): `make clean`