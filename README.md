# Project README

## Overview
This project is a collection of C/C++ utility functions for 3D mathematics, including vector operations, matrix transformations, and geometric calculations.

## Features
- Vector operations (addition, subtraction, dot product, cross product)
- Matrix transformations (translation, rotation, scaling)
- Basic 3D triangle clipping against planes

## Project Structure
```
<Project>/
├── build/              # .exe files produced by Main.c
├── src/                # source code
│   ├── Main.c          # Entry point
│   └── Math3D.h        # Header file containing mathematics functions
└── README.md           # This file
```

### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility

## Build & Run
To build and run the project, follow these steps:

1. **Navigate to the project directory:**
   ```sh
   cd <Project>
   ```

2. **Build the project for Linux:**
   ```sh
   make -f Makefile.linux all
   ```
   To execute:
   ```sh
   make -f Makefile.linux exe
   ```

3. **Build the project for Windows:**
   ```sh
   make -f Makefile.windows all
   ```
   To execute:
   ```sh
   make -f Makefile.windows exe
   ```

4. **Build the project for Wine (Linux cross compile for Windows):**
   ```sh
   make -f Makefile.wine all
   ```
   To execute:
   ```sh
   make -f Makefile.wine exe
   ```

5. **Build the project for Webassembly using Emscripten or wasmtime:**
   ```sh
   make -f Makefile.web all
   ```
   To execute:
   ```sh
   make -f Makefile.web exe
   ```