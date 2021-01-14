---
title: "用hugo结合github建立个人静态网站"
date: 2021-01-14T14:38:08+08:00
---
# hugo生成静态网页

## 安装hugo
1. 访问Github下载Hugo的应用程序，下载地址 https://github.com/gohugoio/hugo/releases 
2. windows请选择下载hugo_0.xx.0_Windows-64bit.zip
3. 下载完成止之后解压文件至C:\Windows\system32，若其他路径需添加到系统环境变量Path中
4. 打开CMD，执行 hugo version 命令验证是否安装成功

```
C:\Users\XXXXXX>hugo version
Hugo Static Site Generator v0.80.0-792EF0F4 windows/amd64 BuildDate: 2020-12-31T13:37:57Z
```
## 本地hugo目录
1. 新建/指定本地目录，通过hugo把站点生成到该目录下 （CMD中）
   $ hugo new site E:/website/second-blog
2. 命令执行后查看E:/website/second-blog目录，查看文件目录结构。
```
│  config.toml
│
├─archetypes
│      default.md
│
├─content
├─data
├─layouts
├─static
└─themes
```
## 安装git
1. 从git官网 https://git-scm.com/downloads/ 下载
2. 安装git

# 安装hugo主题
1. 下载一个主题并加载到config.toml文件中 （CMD中）
 git clone https://github.com/yihui/hugo-ivy.git
2. 通过在 config.toml 配置使用：theme = "hugo-ivy"

另一种方法（未尝试）：
下载一个主题并加载到config.toml文件中：
```
git init
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke

# Edit your config.toml configuration file
# and add the Ananke theme.
echo 'theme = "ananke"' >> config.toml
```

## 生成新的文章 （CMD中）
`hugo new posts/first-post.md`
在content目录中会自动以archetypes/default.md为模板在content/posts目录下生成一篇名为first-post.md的文章草稿：
```
---
title: "First Post"
date: 2021-01-14T14:38:08+08:00
draft: true
---
```
在content/posts目录下打开并编辑，完成后去掉标记为草稿的这一行：draft: true

## 预览
在cmd中使用如下命令建立本地服务器：

>hugo server

在浏览器中输入网址http://localhost:1313/就可以在浏览器中查看网页效果了

## 发布
没有问题了便可以使用如下命令：
>hugo

如此一来网页便生成在默认的public子目录中了。
 
 
 