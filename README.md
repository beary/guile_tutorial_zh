# Guile 入门指南简介

这篇文档介绍了`Guile`的使用，它是`GNU`扩展语言和系统。`Guile`是`Scheme`程序语言的一种方言，我们假设你有`Scheme`或者`LISP`的基础知识。不过，`Guile`也允许应用开发者将它集成到他们的程序中去以提供脚本语言的效率，以及利用其他应用程序的特定的语言来扩展`Guile`原语。

如果你想要开发或者测试你随手写的代码（这是一个好主意，尤其是当你想摆弄的某些东西不方便用文字逐一表达），你需要安装`GNU Guile`（如果你的系统需要的话，还要安装一些包含头文件的开发包）除此之外还有`Gnuplot`，而且要有一个类`UNIX`的环境和`C`编译器（`gcc`就行）。我在一台装有`Guile 1.8.7`、`Gnuplot 4.2`和`gcc 4.3.1`的`Linux`系统的机器上工作，不过任何最新版本的`Guile`和`Gnuplot`都应该可以。

* [基本原理](/chapter1.md)：`Guile`的基本原理
* 乌龟：我们想要实现的乌龟代码包
* Guiling：`Guile`做了什么
* 更进一步：你可以采取的下一步

原文链接：[http://www.gnu.org/software/guile/docs/guile-tut/tutorial.html](http://www.gnu.org/software/guile/docs/guile-tut/tutorial.html)

