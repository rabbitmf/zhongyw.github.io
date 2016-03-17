---
layout: post
title:  "RequireJS的使用"
subtitle:   "RequireJS 归纳笔记"
date:   2016-03-17 11:59:18 +0800
categories: frontend-modules
author:     "zhongyw"
header-img: "img/post-bg-js-module.jpg"
tags:
    - 前端开发
    - JavaScript
---

## Foreword

> Here comes Module!

随着网站逐渐变成「互联网应用程序」，嵌入网页的 JavaScript 代码越来越庞大，越来越复杂。网页越来越像桌面程序，需要一个团队分工协作、进度管理、单元测试……我们不得不使用软件工程的方法，来管理网页的业务逻辑。

于是，JavaScript 的模块化成为迫切需求。在 ES6 Module 来临之前，JavaScript 社区提供了强大支持，尝试在现有的运行环境下，实现模块的效果。


---

## Catalog

1.  [CommonJS & Node](#commonjs--node)
3.  [History](#history)
4.  [RequireJS & AMD](#requirejs--amd)
5.  [SeaJS & CMD](#seajs--cmd)
6.  [AMD vs CMD](#amd-vs-cmd)
7.  [WebPack](#webpack)


