---
layout:     post
title:      "github本地的配置"
subtitle:   "github"
description: "github本地的配置"
keywords: github
date:       2016-02-24 13:19:00
author:     "luanfei"
header-img: 
tags:
    - github
---

### 1.生成新的ssh

```
ssh-keygen -t ras -C "test@gmail.com"
```

### 2.复制～/.ssh/id_rsa.pub

```
在github中增加上面文件内容
```

### 3.测试

```
ssh -T git@github.com
```

### 4.git设置
```
git config --global user.name "username"
git config --global user.email "test@gmail.com"
```
