---
layout:     post
title:      丢掉鼠标，使用键盘操作Chrome学习指南
subtitle:   原生快捷键+Vimium插件使用学习
date:       2019-09-09
author:     fengfeng
header-img: img/post-bg-universe.jpg
catalog: true
tags:
    - Chrome
    - Vim
    - 工作效率
---

## 前言

在换了 `Mac Os` 的操作系统之后，刚开始是由于觉得`Mac Os`的手势非常便捷好用，所以后来慢慢就不使用鼠标了，在日常的开发过程中，都是键盘加上手势来完成工作和学习了，但是后面在`Chrome`浏览器上移动光标的行为，还是会觉得没有鼠标有点麻烦，就试着搜了一下能否单纯只是是用键盘就能流畅快捷的操作了。

然后就发现了 `Vimium` 这个谷歌插件了，接下来我就来学习和演示一下它的神功吧。

## 什么是Vim

作为一个习惯于类unix开发环境的后端程序员，肯定不会对`Vim` 文本编辑陌生了，既然大家已经有不需要使用键盘来操控你的日常开发了的需求，说明应该或多或少的使用过`Vim`了，所以这个我就简单的介绍一下: 

>`Vim`是从 `vi` 发展出来的一个文本编辑器。代码补完、编译及错误跳转等方便编程的功能特别丰富，在程序员中被广泛使用。  

>简单的来说， `vi` 是老式的字处理器，不过功能已经很齐全了，但是还是有可以进步的地方。 `Vim` 则可以说是程序开发者的一项很好用的工具。

## 那什么是Vimium呢

该插件对`Vim`中常用的快捷键在浏览器中进行了相似的隐射，因此对于熟悉`Vim`操作的小伙伴来说，该插件还是非常容易上手的。

> `注意:` 快捷键区分大小写。

## 安装方法
* 需要在科学上网的前提下,r进入Chrome网上应用店下载,搜索[Vimium](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)
* 或者直接去[Github代码仓库](https://github.com/philc/vimium)下载

## 快捷键使用介绍

> 快捷键及其描述比较简单,不做过多的翻译，有些并不是日常会常用的，所以这里只对常用的和有歧义的地方进行描述.

### 当前页面导航

```Vim
?       show the help dialog for a list of all available keys
h       scroll left
j       scroll down
k       scroll up
l       scroll right
gg      scroll to top of the page
G       scroll to bottom of the page
d       scroll down half a page
u       scroll up half a page
f       open a link in the current tab
F       open a link in a new tab
r       reload
gs      view source - 展示的 vimium 的源码，而不是当前页面的源码
i       enter insert mode -- all commands will be ignored until you hit Esc to exit
yy      copy the current url to the clipboard
yf      copy a link url to the clipboard
gf      cycle forward to the next frame
gF      focus the main/top frame
```


### `?`使用
安装完成后，点击 `?`，就会弹出一个快捷键列表的help页面。
![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gicoqlqmjaj30zf0u0ti7.jpg)

