---
title: JS 中的重要概念
date: 2016-12-04 15:12:36
tags:
  - js
  - JavaScript
categories: front-end
---

## 作用域

JS 引擎：从头到尾负责整个 JavaScript 程序的编译及执行过程。

编译器：负责语法分析及代码生成等。

作用域：负责收集并维护由所有声明的标识符（变量）组成的一系列查询，并实施一套非常严格的规则，确定当前执行的代码对这些标识符的访问权限。

## DOM 事件

事件：文档或浏览器窗口中发生的一些特定的交互瞬间。

事件流描述的是从页面中接收事件的顺序，有两种，事件冒泡和事件捕获。

事件冒泡：事件最开始时由最具体的元素接收，然后逐级向上传播到较为不具体的节点。

事件捕获：不太具体的节点更早接收到事件，而最具体的节点最后接收到事件。
