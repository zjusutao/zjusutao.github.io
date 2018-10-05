---
layout: post
title: "「从未体验天下美好，你们去替我看看」"
subtitle: "Shadow, directed by Yimou Zhang"
header-img: "img/post-bg-ying.jpg"
author: "Tao"
header-mask: 0.5
tags:
  - 生活
  - Tools
---

> “只可惜我这一生，只醉心于权谋和征伐，从未看看天下之美。你们替我看看……”

在Github上fork了Hux的博客模板，自己改了一下，又绑定了在万网买的域名[zjusutao.top](http://zjusutao.top/)，博客算是开张了。记录一下过程：

## 安装ruby

Github支持两类博客系统，jekyll和hexo，我选了jekyll，jekyll在本地运行需要ruby语言支持。

## fork和clone模板

现在github上fork模板所在的包，我用的是Hux黄玄小兄弟的，fork完克隆到本地，就可以修改了，当然本地需要安装过git软件。

## 修改各类title信息

把各种原作者的头像、介绍改成自己的，Home页面改完了，但是About页面和Portfolio页面暂时没时间改，先放着，让我们一起敬仰原作者Hux小兄弟。

## 增加文章导航

Hux的文章目录（Table of content）在手机上会隐藏，因此添加了toc.js使目录能在手机上出现，js文件来自于[jekyll-table-of-contents](https://github.com/ghiculescu/jekyll-table-of-contents)。

## 增加跳转到顶部

也是为在手机上阅读方便，增加了jquery.toTop.js，调成了半透明。在电脑上位置不太理想，先不调整了。

## 增加不蒜子统计信息

脚本见：不蒜子  <http://ibruce.info/2015/04/04/busuanzi/> 

## 添加音乐

```html
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="500" height="86" src="//music.163.com/outchain/player?type=2&id=1312166633&auto=0&height=66"></iframe>
```


<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="380" height="86" src="//music.163.com/outchain/player?type=2&id=1312166633&auto=0&height=66"></iframe>
