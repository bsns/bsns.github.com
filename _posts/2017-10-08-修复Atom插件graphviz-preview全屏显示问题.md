---
layout:     post
title:      修复Atom插件graphviz-preview全屏显示问题
subtitle:   Atom
date:       2017-10-08
author:     BSNS
header-img: img/post-bg-desk.jpg
catalog: true
tags:
    - 编辑器
---

## 前言

用atom的插件来预览dot文件，结果发现每次只能显示半个图片。

状态栏部分将atom一分为二，无法正常查看图片

## Mac上的解决方法：

随意的编辑器打开

$HOME/.atom/packages/graphviz-preview/styles/graphviz-preview.less

将最后的部分替换为
```python
iframe, webview {
    width: 100%;
    height: 100%;
    border: 0;
  }
```
替换完成，重启Atom。
