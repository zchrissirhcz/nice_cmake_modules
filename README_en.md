# Nice CMake Modules

<img alt="GitHub" src="https://img.shields.io/github/license/zchrissirhcz/nice_cmake_modules">

[中文版](README.md)

> CMake is cool to use, until find_package() sucks.

## Intro

Put some FindXXX.cmake scripts here, as more accurate alternatives for `<cmake_install_dir>/share/cmake/Modules/FindXXX.cmake`.

Get:
```bash
git clone https://github.com/zchrissirhcz/nice_cmake_modules
```

Integrate:
```bash
list(INSERT CMAKE_MODULE_PATH 0 "/path/to/nice_cmake_modules")
```

Then remove cmake cache if any, otherwise it won't take effect.

## Platform

Android / Windows / Linux / MacOSX

## Module list

[FindZLIB.cmake](FindZLIB.cmake)

## Project origin

See [here](why.md).