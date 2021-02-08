---
title: markdown学习记录
author: catsgarden
avatar: 'https://cdn.jsdelivr.net/gh/catsgarden99/cdn@1.3/img/favicon.ico'
authorLink: catsgarden.top
authorAbout: 只会喊咩夸贴贴
authorDesc: 
categories: 技术
comments: true
date: 2021-02-06 17:12:13
tags:
 - markdown
 - 博客
keywords:
description: markdown使用
photos:
---
# 添加代码块

可以使用`` ` ``来单独高亮一部分文字

可以通过```` ``` ````来添加代码块
```
#just like this example
```
PS:对于多个`` ` ``，比如两个,需加更多的反引号包起来

## 代码高亮

在三个反引号后加所需的语言

```python
# python3
print("Hello, World!")
```

# 文本

## 字体颜色大小

和html基本一致
```
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=5>我是黑体，绿色，尺寸为5</font>
```
## 背景色

```
<table><tr><td bgcolor=yellow>背景色yellow</td></tr></table>
```
<table><tr><td bgcolor=yellow>背景色yellow</td></tr></table>

# 插入图片

```
<img src="picture url">
```
## 图片大小

百分比为width和height均为“80%”

固定像素为“200”

## 图片位置

居中center 左右left right

```
<div align=center><img src="picture url"></div>
```
# 或许有用

[RGB颜色对照表](https://blog.csdn.net/heimu24/article/details/81192697)
[Markdown语法大全](https://blog.csdn.net/qcx321/article/details/53780672)