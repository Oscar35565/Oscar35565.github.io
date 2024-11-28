---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# 如果你想在 Windows 电脑 上体验苹果最新的 macOS 14 Sonoma 系统！ 那么跟着我步骤来进行安装吧~

**

## 安装步骤：

1、首先**下载并安装** VMWare 虚拟机软件【[点击下载](https://www.tuiwo.cc/359.html)】

2. 下载【VMWare Unlocker 】 【[点击下载](https://github.com/paolo-projects/unlocker)】 ，以**管理员身份运行 win-install**

3.**下载 macOS 14 索诺玛 （Sonoma）**的 ISO 系统文件[【点击下载】](https://www.mediafire.com/file/lzlounvkwazy948/macOS+Sonoma+ISO.iso/file)

4.**创建虚拟机，转到我的文档 -> 虚拟机 -> macOS 14 虚拟机文件**，

然后在 **右键单击​​ 2 KB 的macOS 14 (.VMX) 文件**，然后选择使用记事本打开，并在**底部**输入以下内容：

smc.version = "0"

5.正式开始安装

## 6.启用以太网：

搜索 **ethernet0.virtualDev = "e1000e"** 并将
e1000e

替换

 为
**vmxnet3** 
并保存文件。
