---
layout:     post
title:      Excel自增长index
subtitle:   Excel自增长index
date:       2018-03-05
author:     BSNS
header-img: img/post-bg-desk.jpg
catalog: true
tags:
    - Excel
---

## 前言

最近操作数据的时候，还没来得及用数据库，先用csv格式顶着，有时候需要创建一列增长为1的索引

## 步骤

第一步，选中第一行的序号单元格，输入公式“=ROW(AL2)-1”。具体输入 A2 还是 B2、…，参照具体列名即可，如图。  
![](/img/2018/20181127-091057.jpg)  
输入完成后回车确认  
![](../img/2018/20181127-091338.jpg)  
选中生成序号的单元格范围  
![](../img/2018/20181127-091535.jpg)  
回车确认选中,按Ctrl+D生成序号  
![](../img/2018/20181127-091759.jpg)
