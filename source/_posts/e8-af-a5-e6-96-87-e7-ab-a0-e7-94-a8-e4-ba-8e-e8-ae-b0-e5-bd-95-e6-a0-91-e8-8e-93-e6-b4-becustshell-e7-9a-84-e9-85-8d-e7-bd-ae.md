---
title: 该文章用于记录树莓派custshell的配置
id: 252
categories:
  - 未分类
date: 2018-01-07 15:52:24
tags:
---

1.开启ssh功能

	在内存卡根目录新建一个ssh文件

2.打开i2c和camera功能

	sudo raspi-config nonint do_i2c 0 
    sudo raspi-config nonint do_camera 0

3.复制custshell文件到指定目录

4.开启crontab任务