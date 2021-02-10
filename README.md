# Nice CMake Modules

<img alt="GitHub" src="https://img.shields.io/github/license/zchrissirhcz/nice_cmake_modules">

[English Version](README_en.md)

> CMake 一时爽，find_package() 火葬场。

## 简介

放一些 FindXXX.cmake 脚本，作为 cmake 安装路径下 modules 的补充，让 find_package() 准确的找到包。

获取：
```bash
git clone https://github.com/zchrissirhcz/nice_cmake_modules
```

在个人工程中引入:
```cmake
list(INSERT CMAKE_PREFIX_PATH 0 "/path/to/nice_cmake_modules")
```

如果先前有cmake缓存，需要清理后重新执行cmake以生效。

## 目标平台

Android / Windows / Linux / MacOSX

## 模块列表

待添加

## 项目起源

见[此处](why.md)。