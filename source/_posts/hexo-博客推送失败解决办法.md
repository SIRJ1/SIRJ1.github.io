---
title: hexo 博客推送失败解决办法
date: 2022.1.30
updated:
type: solutions
comments:
description:
keywords:
top_img:
mathjax:
katex:
aside:
aplayer:
highlight_shrink:
---

# 关于hexo更新博客内容失败

使用hexo发现博客hexo d更新到github仓库没变化

或者是退回了上一版本的git内容

## 解决方法

在博客目录下使用git bush 输入命令

```
git init
```

进行仓库初始化，然后依次使用

```
hexo clean
hexo g
hexo d
```

更新成功





