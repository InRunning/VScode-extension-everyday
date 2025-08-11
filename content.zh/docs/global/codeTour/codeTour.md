---
weight: 1
bookFlatSection: true
title: "Code Tour"
---
# CodeTour插件

## 推荐指数（1到五颗星）
⭐️⭐️⭐️⭐️⭐️

## 分类
代码阅读

## 简要描述
主要用于代码走读和笔记的插件，记录代码阅读的路径，可以使代码阅读上一个台阶

## 用法
1. 开始记录，调用`CodeTour: Record Tour`命令或在vscode explorer的左下角CodeTour树视图中点击`+`号按钮，这会开始记录一个codeTour，Record Tour还是选择关联git的分支或者commit，一般选择None即可
2. 开始记录后在代码行号左边会显示`+`号按钮，当要记录哪一行并做笔记时，点击`+`号按钮，笔记支持markdown格式，当要记录代码或者保持格式时使用markdown的格式


## 原理
codeTour开始记录后会在项目根目录生成.tour目录，然后每记录一个tour会生成一个对应的文件，文件具体内容格式可以参考https://marketplace.visualstudio.com/items?itemName=vsls-contrib.codetour#:~:text=properly%20discover%20them.-,Tour%20Schema,-title%20(Required)