---
title: Clion QT环境搭建
categories: QT相关
tags:
  - QT
  - 开发环境
---

## 速记

参考文章：

- [在CLion中添加Qt的工具，方便取代Qt Creator](https://www.littlesweet.xyz/2017/04/25/zai-clionzhong-tian-jia-qtde-gong-ju-fang-bian-qu-dai-qt-creator/)

- [在CLion中使用Qt](https://www.littlesweet.xyz/2017/04/06/zai-clionzhong-shi-yong-qt/)

- [【瞎折腾-02】使用CLion搭建Qt开发环境。继续写deepin-menu的内容](https://zhuanlan.zhihu.com/p/31333939)

- [Undefined Qt5 references in C++ using CMake (mingw) in Windows with CLion
](https://stackoverflow.com/questions/28331722/undefined-qt5-references-in-c-using-cmake-mingw-in-windows-with-clion)

- mingw环境要配置 qt tool目录下的：C:\Qt\Qt5.5.1\Tools\mingw492_32
- CMakeLists.txt 文件 set(CMAKE_PREFIX_PATH C://Qt//Qt5.5.1//Tools//mingw492_32) 这个地方设置环境要用双斜杠