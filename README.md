# libft
This was my first project for 42Madrid. It is the starting project of the new cursus.
The aim of this project is to get a deep understanding of the C programming language by rewritting some useful functions and compiling them into a library for future use in other projects. It is completely done in C and compiled using a Makefile.
Some functions (specialy the ones with memory allocation and pointers) may not be optimal, I used them to test how pointers and memory allocation worked using different approaches, I will rewrite them in the future.

## Content
The project consists of 50 functions all written in `.c`, a headerfile `.h` and a `Makefile` to compile them together in a library.

## How to test it?
You can start by cloning this repository:
```bash
git clone https://github.com/jaballest/libft.git libft
```
To compile thisd project you first have to make sure you have all dependencies installed:
```bash
apt update && apt install make binutils clang
```
After this we can just compile:
```bash
make all
```
You can test the library with your own `main.c` and the `libft.h` file.