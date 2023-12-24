# Hi~👋

这是一个基于CMake官方教学文档进行的学习记录📑

# 为什么要学习CMake？🤔

C++是我在大学里接触到的第一门编程语言，虽然学的很不好，但是和C++一见钟情💘，心里一直怀着要使用C++开发的愿景🧑‍💻

同时，在工作中愈发感觉打好计算机基础是很关键的，我已下定决心要好好学习一番[OpenGL](https://learnopengl.com/Getting-started/Creating-a-window)，学好C++是入门OpenGL的第一步！

# 这个仓库存在的意义是什么？

我是一个很不愿意整理的人，我前前后后换过好多台设备，每一次更新设备后，旧设备上的大多数据都随着老设备一起被丢弃掉了，我觉得很可惜，将所有自己学的东西都丢到Github上，不怕丢，也更有程序员的范儿～

在学习CMake的过程中我经常犯一些很蠢的错误，我会把这些地方搞清楚后记录在这里，给自己，或者给路过🚶的你一点小小的提醒⏰！

# 学习日志

## 2023-12-24

使用的CMake版本是3.28.1

在[官方教程](https://cmake.org/cmake/help/latest/guide/tutorial/A%20Basic%20Starting%20Point.html)Exercise 3 - Adding a Version Number and Configured Header File的TODO9中

```cmake
target_include_directories(Tutorial PUBLIC "${PROJECT_BINARY_DIR}")
```

因为少打了{PROJECT_BINARY_DIR}前面的$号导致找不到头文件😅
