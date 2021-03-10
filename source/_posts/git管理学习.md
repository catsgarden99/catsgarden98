---
title: git管理学习
author: catsgarden
avatar: 'https://cdn.jsdelivr.net/gh/catsgarden99/cdn@1.3/img/favicon.ico'
authorLink: catsgarden.top
authorAbout: 只会喊咩夸贴贴
categories: 笔记
comments: true
date: 2021-03-04 15:57:35
tags:
 - git
 - github
description:
photos: https://cdn.jsdelivr.net/gh/catsgarden99/blogcdn@1.1/posts/%E6%96%87%E7%AB%A0%E9%BB%98%E8%AE%A4.jpg
---

# 初始化本地仓库
```cmd
 git init                                  # 初始化
 git add README.md                         # 添加文件
 git commit -m "添加 README.md 文件"        # 提交并备注信息
```

# 提交到 Github
```cmd
 #接需要的仓库
 git remote add origin git@github.com:catsgarden99/blogcdn.git
 #接上传到的分支，默认的是main
 git push -u origin master
```
# 后期上传
```cmd
#在第一次配置好后，仅需提交及上传
 git commit -m "添加 README.md 文件"  
 git push -u origin master
```

# 一些用得到的参考：
[<font size=5>Git 上传文件、文件夹、项目到 Github</font>](https://blog.csdn.net/jerryhanjj/article/details/72777618)
[<font size=5>菜鸟教程</font>](https://www.runoob.com/git/git-remote-repo.html)
