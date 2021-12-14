# 安装 hexo-generator-searchdb，在站点的根目录下执行以下命令：

``` shell
$ npm install hexo-generator-searchdb --save
```


### 1. 下载hexo-themes-Shier

+ **最新版**：进入 /Hexo目录/themes：

``` shell
git clone git@github.com:wt812/hexo-theme-Shier.git
```

### 2. 修改Hexo目录下的_config.yml 的 **theme** 为 **hexo-themes-shier**

### 3. 语言配置

请在hexo文件下的"_config.yml"修改 **language** 为 **en** 或者 **zh-Hans**， 目前只支持这两种语言


### 4. 修改配置

````yaml
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
````

### 5. 404 页面配置：

#### 在hexo跟目录的Source文件夹下创建一个404.md，并写入如下内容:

``` markdown
---
title: 404
type: "404"
layout: "404"
---
```
> 如果你对这个项目感兴趣也可以一起合作🤝

---

### 如果喜欢请送上一个star✨～

### 如果你对我的研究感兴趣期待你的follow👬～🌈

