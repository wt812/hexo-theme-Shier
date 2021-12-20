# hexo-themes-Shier

[Demo](http://zaole.net "Notebook")


# 主体

简约、美观、实用<Br>
如果有任何建议欢迎issue，也可以提出pr。<Br>
如果喜欢请送上一个star✨～<br>
如果你对我的研究感兴趣期待你的follow👬～🌈<br>


# 改进

+ 支持概要多图展示
+ 支持仅标题展示
+ 支持概要图文展示
+ 支持搜索
+ 支持黑白style
+ 支持文章密码查看
+ 优化了css文件，优化了主题的颜色等，将部分css改为stylus方便编译
+ 调整了部分选项的可选性
+ 增加了nav menu的编辑支持
+ 增加了文章底部的copyright栏
+ 优化了部分代码
+ 兼容移动端浏览器预览


# 使用

## 安装

#### 1. 安装hexo-themes-Shier主题

``` shell
git clone git@github.com:wt812/hexo-theme-Shier.git

```
或者直接下载主题zip包解压至主题目录下，重命名为Shier


#### 2. search依赖 hexo-generator-searchdb

``` shell
$ npm install hexo-generator-searchdb --save

```


#### 3. 文章加密依赖 hexo-blog-encrypt
```shell
$ npm install --save hexo-blog-encrypt

```


#### 4. 图片懒加载依赖 Hexo-lazyload-image
```shell
$ npm install hexo-lazyload-image --save

```
在站点的根目录下执行以下命令


## 配置


#### 1. 修改Hexo目录下的_config.yml的theme修改为 **Shier**

#### 2. 语言配置

请在hexo文件下的"_config.yml"
修改 **language** 为 `en` 或者 `zh-Hans`， 目前只支持这两种语言


#### 3. 修改配置

```shell
# 当前版本 | Theme Version
Hexo: "2.1"

#语言 | Language
# en | zh-Hans
#请在hexo文件下的"_config.yml"修改language
language: en

# 网站标题 | Title
logo_title: '🙏🏾'

# 初始化风格 | Default Style "black/light"
# style: black
style: light

#SEO优化

## 网站描述
description: 欢迎👏🏻

## 网站关键词：用英文逗号分割
keywords: notebook

# 首页URL | Your URL
link: Your_URL

# 你的昵称 | Your Name
author: Your Name

#hexo links
hexo_links: https://hexo.io

# 站点小图标地址 | Small Icon of Your Site
favicon: /img/favicon.ico

# 菜单栏配置 | Nav Bar Settings
menu:
  2012至今: /
  Markdown: /Markdown

# 站内关键词搜索 | Local Search
search:
 enable: true
 path: search.xml
 field: post
 # onload: true

# 评论系统 | Comments
## 做了域名限制，请改成自己的 KEY
## 若关闭valine 设置enable为false
valine:
  enable: true
  appId: 
  appKey: 

# visitors count
counter:
  enable: true

highlight:
  enable: true
```

#### 4. 404 页面配置：

在hexo跟目录的Source文件夹下创建一个404.md，并写入如下内容:

``` markdown
---
title: 404
type: "404"
layout: "404"
---
```
> 如果你对这个项目感兴趣也可以一起合作🤝