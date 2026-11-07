# multi

CMake 多文件项目：编译、链接与增量构建。

## 结构

- `add.h` / `add.cpp` — 加法函数，声明与实现分离
- `main.cpp` — 调用方
- `CMakeLists.txt` — 构建配置

## 构建

cmake -S . -B build
cmake --build build -j
./build/app
