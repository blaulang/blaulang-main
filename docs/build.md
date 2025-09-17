# Build and Installation Guide

This document describes how to build and install Blaulang.

## Prerequisites
- C++17 compatible compiler (GCC 9+, Clang 10+, MSVC 2019+)
- CMake 3.15+
- Make or Ninja

## Build Steps
```bash
git clone https://github.com/blaulang/blaulang-main.git
cd blaulang-main
mkdir build && cd build
cmake .. -DCMAKE_BUILD_TYPE=Release
make -j4
```

## Run
```bash
./blaulang ../examples/hello.bll
```

## Install
```bash
sudo make install
```
