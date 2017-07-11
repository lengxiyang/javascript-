## 一、JavaScript 概述

JavaScript是一种轻量级的脚本语言。所谓“脚本语言”，指的是它不具备开发操作系统的能力，而是只用来编写控制其他大型应用程序的“脚本”。

JavaScript是一种嵌入式（embedded）语言。它本身提供的核心语法，规模相当小，只能用来做一些数学和逻辑运算。JavaScript本身不提供任何与I/O（输入/输出）相关的API，都要靠宿主环境（host）提供，所以JavaScript只合适嵌入更大型的应用程序环境，去调用宿主环境提供的底层API。

目前，已经嵌入JavaScript的宿主环境有多种，最常见的环境就是浏览器，另外还有服务器环境，也就是Node项目。

从语法角度看，JavaScript语言是一种“对象模型 ”语言。各种宿主环境通过这个模型，描述自己的功能和操作接口，从而通过JavaScript控制这些功能。但是，JavaScript并不是纯粹的“面向对象语言”，还支持函数式编程。这导致几乎任何一个问题，JavaScript都有多种解决方法。

JavaScript的核心语法部分相当精简，只包括两个部分：基本的语法构造（比如操作符、控制结构、语句）和标准库（就是一系列具有各种功能的对象比如Array、Date、Math等）。除此之外，各种宿主环境提供额外的API（即只能在该环境使用的接口），以便JavaScript调用。以浏览器为例，它提供的额外API可以分成三大类。

浏览器控制类：操作浏览器
DOM类：操作网页的各种元素
Web类：实现互联网的各种功能
如果宿主环境是服务器，则会提供各种操作系统的API，比如文件操作API、网络通信API等等。这些你都可以在Node环境中找到。

## 二、为什么学习 JavaScript

JavaScript语言有一些显著特点，使得它非常值得学习。它既适合当作学习编程的入门语言，也适合当作日常开发的工作语言。它是目前得发展最好、最热门的计算机语言之一。无论是从事Web前端开发还是从事后台数据操作的开发人员都可以去使用它。

JavaScript的发明目的，就是作为浏览器的内置脚本语言，为网页开发者提供操控浏览器的能力。它是目前唯一一种通用的浏览器脚本语言，所有浏览器都支持。它可以让网页呈现更多特殊效果，扩展Web页面或者应用的功能，为用户提供良好的互动体验。

目前，全世界几乎所有网页都使用JavaScript。如果不去使用它，那么网站的易用性和使用效率将大打折扣，而且在功能需求上都会存在诸多的限制，的很难满足现代浏览器或应用挑剔的用户的“味口”的，从而让自己的项目产品失去竞争力、失去用户。

对于一个互联网开发者来说，如果你想提供漂亮的网页、令用户满意的上网体验、各种基于浏览器的便捷功能、前后端之间紧密高效的联系，JavaScript是必不可少的。

## 三、JavaScript 应用领域

近年来，正是JavaScript所具有的灵活的语法特性和轻量化以及高运行性能的优势，使得它的使用范围，慢慢超越了浏览器，正在向通用的系统语言发展，正是“遍地开花”之时。

- 浏览器的平台化：

    随着HTML5的出现，浏览器本身的功能越来越强，不再仅仅能浏览网页，而是越来越像一个平台，JavaScript因此得以调用许多系统功能，比如操作本地文件、操作     图片、调用摄像头和麦克风等等。这使得JavaScript可以完成许多以前无法想象的事情。
    
 - Node

    Node项目使得JavaScript可以用于开发服务器端的大型项目，网站的前后端都用JavaScript开发已经成为了现实。目前，有越来越多的嵌入式平台能够安装           Node.js，于是JavaScript就能为这些平台开发应用程序。
    
  - 数据库操作

    JavaScript甚至也可以用来操作数据库。NoSQL数据库这个概念，本身就是在JSON（JavaScript Object Notation，JavaScript对象表示法）格式的基础上诞生     的，大部分NoSQL数据库允许JavaScript直接操作。基于SQL语言的开源数据库PostgreSQL支持JavaScript作为操作语言，可以部分取代SQL查询语言。
    
  - 跨移动平台

    JavaScript也正在成为手机应用的开发语言。一般来说，Android平台使用Java语言开发，iOS平台使用Objective-C或Swift语言开发。许多人正在努力，让         JavaScript成为各个平台的通用开发语言。PhoneGap项目就是将JavaScript和HTML5打包在一个容器之中，使得它能同时在iOS和Android上运行。Facebook的       React Native项目则是将JavaScript写的组件，编译成原生组件，从而使它们具备优秀的性能。Mozilla基金会的手机操作系统Firefox OS，更是直接将           JavaScript作为操作系统的平台语言。
    
## 四、JavaScript 易学性

相比学习其他语言，学习JavaScript有一些有利条件：

  - 学习环境无处不在

    只要有浏览器，就能运行JavaScript程序；只要有文本编辑器，就能编写JavaScript程序。这意味着，几乎所有电脑都原生提供JavaScript学习环境，不用另行安     装复杂的IDE（集成开发环境）和编译器。

  - 简单性

    相比其他脚本语言（比如Python或Ruby），JavaScript的语法相对简单一些，本身的语法特性并不是特别多。而且，那些语法中的复杂部分，也不是必需要学会。     你完全可以只用简单命令，完成大部分的操作。

  - 与主流语言的相似性

    JavaScript的语法很类似C/C++和Java，如果学过这些语言，JavaScript的入门会非常容易。
    必须说明的是，虽然核心语法不难，但是JavaScript的复杂性体现在另外两个方面。
    首先，它涉及大量的外部API。JavaScript要发挥作用，必须与其他组件配合，这些外部组件五花八门，数量极其庞大，几乎涉及网络应用的各个方面，要掌握它们     绝非朝夕之事。
    其次，JavaScript语言有一些设计缺陷。某些地方相当不合理，另一些地方则会出现怪异的运行结果。学习JavaScript，很大一部分时间是用来搞清楚哪些地方有     陷阱，如浏览器的兼容性。

    尽管如此，目前看来，JavaScript的地位还是无法动摇。加之，语言标准的快速进化，使得JavaScript功能日益增强，而语法缺陷和怪异之处得到了弥补。所以，     JavaScript还是值得学习，而作为一个Web前端开发工程师，基本上是必学的，况且它的入门相对于其它编程语言的确是非常简单的。
    
## 五、JavaScript 性能

JavaScript的性能优势体现在以下方面:

  - 语法灵活，表达力强

    JavaScript既支持类似C语言清晰的过程式编程，也支持灵活的函数式编程。可以用来写并发处理。这些语法特性已经被证明非常强大，可以用于许多场合，尤其适     用非同步编程。

    JavaScript的所有值都是对象，这为程序员提供了灵活性和便利性。因为你可以很方便地、按照需要随时创造数据结构，不用进行麻烦的预定义。

    JavaScript的标准还在快速进化中，并不断合理化，并添加更适用的语法特性

   - 支持编译运行

     JavaScript语言本身，虽然是一种解释型语言，但是在现代浏览器中，JavaScript都是编译后运行。
    
     程序会被高度优化，运行效率接近二进制程序。而且，JavaScript引擎正在快速发展，性能将越来越好。

   - 事件驱动和非阻塞式设计

     JavaScript程序可以采用事件驱动和非阻塞式设计，在服务器端适合高并发环境，普通的硬件就可以承受很大的访问量。
    
## 六、JavaScript 引入方式

### 1、内嵌方式

直接在 html 文档的 head 或 body 标签中嵌入 js，如下所示：

    <!DOCTYPE html>
    <html lang="en">
    <head>
	    <meta charset="UTF-8">
	    <title>Document</title>
        <script>
        // insert javascript codes in here....
        </script>
    </head>
    <body>
        <script>
        // insert javascript codes in here....
        </script>
    </body>
    </html>
    
 tips：script 标签可以放在网页任意位置，通常不建议这样使用，而是将 JavaScript 代码独立放到一个文件中再引入使用，即后面要讲到的外链引入方式。
 
 ### 2、外链方式
 
 创建 .js 文件，在 head 标签内或在 body 结束标签前引入。引入 .js 文件使用 script 标签，并通过 src 属性指定文件路径，代码如下：
 
    // my.js

    // insert javascript codes in here...
    <!-- index.html -->
    <!DOCTYPE html>
    <html lang="en">
    <head>
	    <meta charset="UTF-8">
	    <title>Document</title>
        <!-- 引入方式1 -->
        <script type="text/javascript" src="my.js"></script>
    </head>
    <body>
        <!-- 引入方式2 -->
	    <script type="text/javascript" src="my.js"></script>
    </body>
    </html>
    
 tips：这里建议大家使用外链方式，将js代码独立放置到一个文件中，便于我们后期维护整合优化。


#### 注：本课主要内容参考了阮一峰老师的著作《JavaScript 标准参考教程（alpha）》
