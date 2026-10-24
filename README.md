# Smart File Analyzer

A command-line tool written in modern C++ for analyzing files.

![Status](https://img.shields.io/badge/status-early%20stage-lightgrey)
![C++20](https://img.shields.io/badge/C++-20-00599C?logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/build-CMake-064F8C?logo=cmake&logoColor=white)

## Status

🚧 Early stage. The repository currently contains the project setup: a C++20 CMake
build and a minimal entry point. The analysis features are being built next.

## Build and run

Requirements: a C++20 compiler (GCC 10+, Clang 12+ or MSVC 2019+) and CMake 3.16+.

```bash
git clone https://github.com/newfreshhorizonx/smart-file-analyzer.git
cd smart-file-analyzer
cmake -S . -B build
cmake --build build
./build/smart-file-analyzer        # Windows: build\Debug\smart-file-analyzer.exe
```

## Project structure

```
smart-file-analyzer/
├── CMakeLists.txt   # build configuration (C++20)
└── src/
    └── main.cpp     # entry point
```
