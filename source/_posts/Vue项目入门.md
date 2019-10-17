---
title: Vue项目入门
date: 2019-10-16 17:51:37
tags:
---
# Node.js的安装
## 1 下载Node.js
[下载网址](https://nodejs.org/en/download/)

自己下载的Windows64位的，各位根据自己的需求下载就好啦。
## 2 安装Node.js
Node.js的安装呢，自己鼓捣一下，傻瓜式安装，一路next下去，选取安装位置就行，我自己装到了D盘里，重点放在后文。
## cnpm安装
npm是Node.js的包管理器，在后期开发中下载各种组件

cnpm是npm的中国国内镜像版

Node.js是自带npm的，但是由于访问外网比较慢，所以我自己是推荐安装cnpm的。

打开cmd，运行下面语句，安装cnpm。

```bash
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

# Vue脚手架搭建

## 1 安装vue-cli

在cmd中输入命令

```bash
cnpm install -g vue-cli
```
