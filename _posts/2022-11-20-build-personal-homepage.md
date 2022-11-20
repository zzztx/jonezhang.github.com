---
title: Bulid Personal Homepage
layout: post
post-image: "assets/images/title/build_personal_homepage.png"
description: Published on November 19, 2022.
tags:
- technology
- memo
- selfuse
---

This post will show you how to build a personal homepage.

---

## Jekyll安装与使用：

##### ruby：

- jekyll的底层引擎是基于ruby的。通过[ruby官网](https://rubyinstaller.org/downloads/)下载即可。
- 勾选三个选项（加入环境变量、默认打开后缀文件、默认编码utf-8）
- MSYS2是ruby常用开发工具，可选。
- 安装后回车出现succeeded即成功。

##### jekyll：

- 安装命令

  ```linux
  gem install jekyll
  
  # 如果国内下载慢可考虑换源
  gem sources --remove https://rubygem.org/
  gem source -a https://gems.ruby-china.org/
  ```

- 运行命令

  ```linux
  # 启动jekyll主题博客
  jekyll serve
  
  # 创建简单博客
  jekyll new blog
  cd blog 
  jekyll serve
  ```

- jekyll博客通过markdown进行书写，推荐[typora编辑器](https://typoraio.cn/)。
- 免费[jekyll博客主题](http://jekyllthemes.org/)

## 域名购买与解析：

- 阿里云购买域名
- 域名列表进行解析
  - 记录类型：A
  - 主机记录：@
  - 记录值：ping zzztx.github.io后得到的ip值
  - TTL：10分钟

## Github Page：

- new repository：新建存储库
- Repository name：存储库命名
- Add a README file：添加readme文件
- code复制HTTPS到本地git clone url
- 添加jekyll project
- git add .
- git commit -m "修改说明"
- git push
- 进入github的project页面
- settings的pages选项
- coustom domain中填入自己的域名，等待check



















