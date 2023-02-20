---
title: 第一节课
description: 
published: 1
date: 2023-02-20T10:47:31.205Z
tags: 
editor: markdown
dateCreated: 2023-02-16T02:41:19.258Z
---

# Linux系统应用

## 泛雅
1. 签到
2. 作业
3. 上课笔记，资料 / 视频 -> B站
4. 考试
![](/linux_note_image/2023-02-16-08-07-20.png)

## 考察方式
1. 平时:期末 = 3:7
2. 平时，签到 + 作业
3. 期末，闭卷上机，泛雅考试

## 我
1. 邓招奇
2. B706
3. 课后问题
   - 学习通
   - QQ: 5396 2791  <-  学委  备注
   - email: zhaoqid@zsc.edu.cn
4. 尽量在课上提问

## 课程
1. 内容：Linux系统的使用，管理，编程工具，系统编程，shell编程，数据处理
2. 编程
   - C语言
   - 系统调用
3. shell 脚本
   - 利用shell流程控制，融合Linux命令，完成自动化的操作

## 系统
```mermaid
graph TD 

宏内核 --> Windows 
宏内核 --> Unix

BSD --> MacOS/OSX
Unix --> BSD --> IOS
Unix --> Linux --> Android

Linux --提供--> 服务 --> App

微内核 --> Harmony --> App
```

## Linux发行版
1. Windows 版本 1.0 -> 11
   - Desktop
   - Server
2. RedHat 商业版
   - 免费的社区版
   - Fedora 桌面 
   - CentOS 服务器  -> 利用命令行来操作系统
3. Debian 免费
   - Ubuntu 桌面 / 服务器
   - 偶数年的4月份，发布LTS，5-7年
   - 2204 LTS
   - 其他短期版本，9个月
4. ArchLinux
5. 发行版的下载
   - 官网
   - [清华](https://mirrors.tuna.tsinghua.edu.cn/)
   - ISO文件

## 实验室FTP
1. ubuntu-20.04.3-live-server-amd64.iso
2. Filezilla 
   ![](/linux_note_image/2023-02-16-09-03-57.png)
3. FTP 
   ![](/linux_note_image/2023-02-16-09-04-34.png)
4. 目录
   ![](/linux_note_image/2023-02-16-09-05-44.png)
5. 直接拖动下载
   - 默认下载 当前登录用户的 DZ C:\Users\DZ\

## 安装Linux系统
1. 真实硬件上安装
   - 已有Windows 
   - Ubuntu 和 Win 共存
   - 小心，不要丢数据，免责声明
   - ISO镜像 -> U盘
2. 建议初学者，在虚拟硬件上安装
3. 虚拟机: 在宿主Windows下，用软件的方式模拟一台电脑，不破坏宿主机系统和数据
4. 虚拟机软件
   - WmWare WorkStation 商业版 
   - WmWare Player 
   - Virtual Box    

## 新建虚拟机
1. Vm 
   ![](/linux_note_image/2023-02-16-09-14-23.png)
2. 新建虚拟机
   ![](/linux_note_image/2023-02-16-09-15-12.png)
3. 典型 
   ![](/linux_note_image/2023-02-16-09-15-41.png)
4. 稍后安装 
   ![](/linux_note_image/2023-02-16-09-16-07.png)
5. Ubuntu 64 
   ![](/linux_note_image/2023-02-16-09-16-43.png)
6. 名字和保存目录
   ![](/linux_note_image/2023-02-16-09-18-28.png)
7. 硬盘
   ![](/linux_note_image/2023-02-16-09-19-02.png)
8. 自定义硬件
   ![](/linux_note_image/2023-02-16-09-19-33.png)
9. 假设完成 -> 编辑虚拟机设置
    ![](/linux_note_image/2023-02-16-09-20-16.png)
10. CPU 
    ![](/linux_note_image/2023-02-16-09-21-15.png)
11. 设置光盘镜像位置
    ![](/linux_note_image/2023-02-16-09-22-37.png)

## Markdown / md 文件
1. typora打开
2. 安装 typora-setup-x64.exe
3. 或者 VS code 
   - 需要 安装 Markdown 插件
  
## 安装系统 
1. power on 
   ![](/linux_note_image/2023-02-16-09-30-47.png)
2. 鼠标点进 虚拟机 
   - Ctrl + Alt 退出虚拟机
3. 只能用键盘
   - 上下键，或者 tab键 
   - Enter 确定，下一步
4. 选择语言
   ![](/linux_note_image/2023-02-16-09-33-20.png)
5. 不更新 installer 
   ![](/linux_note_image/2023-02-16-09-37-02.png)
6. 键盘布局 默认 English 
   ![](/linux_note_image/2023-02-16-09-37-53.png)
7. 自动获得IP地址
   ![](/linux_note_image/2023-02-16-09-39-24.png)
8. 代理服务器为空
   ![](/linux_note_image/2023-02-16-09-39-58.png)
9. 设置mirror address 
   - https://mirrors.huaweicloud.com/ubuntu
   ![](/linux_note_image/2023-02-16-10-08-01.png)
10. 使用整个磁盘
    ![](/linux_note_image/2023-02-16-10-09-18.png)
11. 磁盘分区信息
    ![](/linux_note_image/2023-02-16-10-11-15.png)
12. 确认磁盘操作
    ![](/linux_note_image/2023-02-16-10-12-28.png)
13. 设置用户名密码  test / asdf 
    ![](/linux_note_image/2023-02-16-10-14-01.png)
14. 默认不安装 Openssh server
    ![](/linux_note_image/2023-02-16-10-14-47.png)
15. 默认不选择安装任何服务
    ![](/linux_note_image/2023-02-16-10-15-42.png)
16. 安装系统
    ![](/linux_note_image/2023-02-16-10-16-23.png)

