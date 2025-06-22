---
layout: post
title: "The first blog!"
date: 2025-06-05 15:13:18 +0200
image: 11.jpg
tags: [jekyll, docs]

categories: jekyll
--- 
##### 这是一个测试，测试能否正常发布博客。简单叙述一些搭建博客过程, 

1丶首先需要安装ruby和jekyll这两个前置依赖。安装都比较简单粗暴，首先需要再对应的官网（jekyll https://jekyllrb.com/）官网进行下载，安装教程进行安装。主要注意两点在安装ruby的时候需要添加到环境变量当中，在安装jekyll的时候有可能会因为网络原因安装不成功，建议切换到国内镜像源进行安装。

2丶在github上找到自己想要的jekyll主题,推荐一个网站 http://jekyllthemes.org/ 在上面选择合适的主题clone到本地，记得修改远端的地址（不然push不到自己分支 这里我是使用直接下载压缩文件，然后在本地复制的主要是git用的比较差 弄了半天没弄好）

3丶修改_config.yal文件后为自己的信息，然后可以拉起服务本地看一些，主要是

```bash
bundle install  #安装依赖

bundle exec jekyll build   #生成 _site 文件夹，里面是编译好的静态网页（HTML、CSS、JS 等）

bundle exec jekyll serve  #启动服务器
```

4丶push到自己的git仓库就可以了（有部分信息没有补充，先休息 明天还要上班）