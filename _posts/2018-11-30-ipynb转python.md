---
layout:     post
title:      ipynb转python
subtitle:   固件错误
date:       2018-11-30
author:     BSNS
header-img: img/post-bg-desk.jpg
catalog: true
tags:
    - python
---

## 前言

将ipynb格式的文件转换为py格式文件


## 安装ipynb
下载学习他人的python写法，加入需要将ipynb格式转码为py格式  
![](/img/2018/2018-12-03 16-13-42.png)  
ubuntu下直接用命令
```
sudo apt install ipython3
```
安装完成后直接尝试
```
ipython3 nbconvert --to=python [YOUR_NOTEBOOK].ipynb
```
![](/img/2018/2018-12-03 16-24-59.png)
## 安装ipynb(python2)。
假如直接安装python2版本的ipynb，在转码的时候还会提示  
![](/img/2018/2018-12-03 16-17-00.png)   
就需要后续安装
pip install nbconvert
