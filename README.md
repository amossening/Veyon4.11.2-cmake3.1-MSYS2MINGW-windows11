# Veyon4.11.2-cmake3.1-MSYS2MINGW-windows11
使用MSYS2 MINGW完整编译Veyon4.11.2源码，部署到Windows运行

## 项目介绍
Veyon是开源跨平台电子教室/机房监控管理软件，可实时监控学生电脑屏幕、屏幕广播、远程控制、锁屏、分发文件、远程开关机。
本仓库为Veyon 4.11.2源码，基于 MSYS2 + MinGW + CMake3.1 在Windows11平台完整编译适配版本。

## 软件界面预览
![Veyon Master主界面](./assets/veyon-ui.png)

## ✨ 功能特性
- 实时屏幕监控，多台电脑缩略图预览
- 屏幕广播演示（教师画面推送到所有客户端）
- 远程控制学生电脑、远程协助
- 一键锁定屏幕，禁止学生操作
- 批量发送消息、分发文件
- 远程开机/关机/重启计算机

## 🛠️ 编译环境
- OS：Windows11
- 编译工具链：MSYS2 + MinGW-w64
- CMake：3.1+
- Qt：6

## 📦 编译步骤
1. 安装 MSYS2，更新包管理器
2. 安装依赖：Qt、cmake、gcc等
3. cmake 配置
4. make 编译
5. 打包部署
<img width="1384" height="736" alt="image" src="https://github.com/user-attachments/assets/65baa0b7-128b-4cf6-a171-65beee066376" />

![Uploading image.png…]()

## 📄 License
GPL-3.0
