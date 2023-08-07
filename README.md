览沃 Livox-SDK 安装（简洁版）

[English Version of the README](<https://github.com/Livox-SDK/Livox-SDK/blob/master/README.md>) 

[中文版本使用说明](<https://github.com/Livox-SDK/Livox-SDK/blob/master/README_CN.md>)


# 1. 安装依赖
以下将介绍 Ubuntu 18.04/16.04/14.04 LTS 系统、 Windows 7/10 系统和 ARM-Linux 交叉编译的安装过程. 对于 Ubuntu 18.04/16.04/14.04 32-bit LTS 和 Mac 系统, 您可以查阅 [Livox-SDK wiki](https://github.com/Livox-SDK/Livox-SDK/wiki)。

Livox SDK 依赖于 cmake 。你可以通过 apt 工具安装这些依赖包 :
```
sudo apt install cmake
```
# 2. 编译 Livox SDK

在 Livox SDK 目录中，执行以下指令编译工程:
```
git clone https://github.com/Livox-SDK/Livox-SDK.git
cd Livox-SDK
cd build && cmake ..
make
sudo make install
```
