### jekyll   http://jekyll.bootcss.com/

```
_config.yml: 配置文件
_layouts: 模板文件
_post: 博客的内容，year-month-date-file.m
_includes: 可重复利用的文件.
_site: 存放最终生成的文件
对于目录下的每个文件，使用YAML Front Matter(---   ---)之后，都会被转格式，然后生成最终文件。
*头信息
---
layout: post
title: xxxxx
pemalink: /hello/ #让博客中的URL地址不同于默认值 /year/month/day/title.html 
category: tech
---

```

