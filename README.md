# Hikvision Camera SDK (Python)

Hikvision 摄像机 SDK Python 封装库

## 安装

使用 pip 直接从 GitHub 安装：

```bash
pip install git+https://github.com/suger-coffee/hikvision-sdk-python.git

```

## 替换

```python
# 原示例写法（本地相对导入）
from CameraParams_header import *

# 推荐写法（使用 pip 包的绝对导入）
from hikvisionSDK.CameraParams_header import *

# 与海康官方示例一致的“裸变量风格”
# 避免原始示例中大量常量、结构体和别名因命名空间不匹配而产生报错
```

## 版本

v4.6.0.1

## 免责声明

This project is NOT an official Hikvision product.

It is an independent Python wrapper created only for learning, development, and 
integration convenience. This repository does NOT contain any Hikvision proprietary 
DLLs, SDK binaries, drivers, or confidential materials. All functionalities require 
the user to install the official Hikvision MVS SDK separately.

Please comply with the Hikvision SDK license agreement when using this project.

本项目并非海康威视官方产品，与海康威视无任何隶属关系。

本仓库仅提供对公开工业相机 SDK 的 Python 封装，旨在方便学习与开发使用。
本仓库不包含任何海康威视官方的 DLL、SDK 二进制文件、驱动程序或未公开资料。
所有功能需用户自行安装海康官方的 MVS 工业相机 SDK。

使用本项目时请遵循海康威视官方 SDK 的许可协议。


