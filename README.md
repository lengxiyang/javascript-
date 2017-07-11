主要是涉及JavaScript基础知识的回顾。


一、JavaScript 概述

JavaScript是一种轻量级的脚本语言。所谓“脚本语言”，指的是它不具备开发操作系统的能力，而是只用来编写控制其他大型应用程序的“脚本”。

JavaScript是一种嵌入式（embedded）语言。它本身提供的核心语法，规模相当小，只能用来做一些数学和逻辑运算。JavaScript本身不提供任何与I/O（输入/输出）相关的API，都要靠宿主环境（host）提供，所以JavaScript只合适嵌入更大型的应用程序环境，去调用宿主环境提供的底层API。

目前，已经嵌入JavaScript的宿主环境有多种，最常见的环境就是浏览器，另外还有服务器环境，也就是Node项目。

从语法角度看，JavaScript语言是一种“对象模型 ”语言。各种宿主环境通过这个模型，描述自己的功能和操作接口，从而通过JavaScript控制这些功能。但是，JavaScript并不是纯粹的“面向对象语言”，还支持函数式编程。这导致几乎任何一个问题，JavaScript都有多种解决方法。

JavaScript的核心语法部分相当精简，只包括两个部分：基本的语法构造（比如操作符、控制结构、语句）和标准库（就是一系列具有各种功能的对象比如Array、Date、Math等）。除此之外，各种宿主环境提供额外的API（即只能在该环境使用的接口），以便JavaScript调用。以浏览器为例，它提供的额外API可以分成三大类。

浏览器控制类：操作浏览器
DOM类：操作网页的各种元素
Web类：实现互联网的各种功能
如果宿主环境是服务器，则会提供各种操作系统的API，比如文件操作API、网络通信API等等。这些你都可以在Node环境中找到。
