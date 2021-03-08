---
title: change blog theme
data: 2021-03-08 19:23
categories: [blog]
tags: jekyll

---

# 找到自己想要的主题

    GitHub.com #jekyll-theme repos
    jamstackthemes.dev
    jekyllthemes.org
    jekyllthemes.io
    jekyll-themes.com
在jekyllthemes.org找到Chirpy主题，打算换掉原来的主题

## 更换过程
在Gemfile中添加：
```bash
gem "jekyll-theme-chirpy"
```
然后，添加这行到您的jekyll项目的_config.yml中：
```bash
theme:jekyll-theme-chirpy
```
最后执行：
```bash
$bundle
```

