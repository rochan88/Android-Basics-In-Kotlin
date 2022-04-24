# **Kotlin 简介**
学习 Kotlin 这个现代编程语言的基础知识，以你明了的方式表达的思路。

##  1. 欢迎学习《使用 Kotlin 进行 Android 开发的基础知识》 
********
[![Watch the video](https://img.youtube.com/vi/OpQ3VzzgE0g/maxresdefault.jpg)](https://youtu.be/OpQ3VzzgE0g)


<!--https://redirector.gvt1.com/edgedl/cn-devsite/OpQ3VzzgE0g.mp4-->

********
认识 Android 团队，了解要开始使用 Kotlin 开发 Android 应用需具备哪些条件。
## 2. 使用 Kotlin 构建您的第一个 Android 应用
***
<!--iframe frameborder=0 src="//redirector.gvt1.com/edgedl/cn-devsite/7VG8b7FtTo0.mp4">
</iframe-->
[![Watch the video](https://img.youtube.com/vi/7VG8b7FtTo0/maxresdefault.jpg)](https://youtu.be/7VG8b7FtTo0)

***
观看这个对第 1 单元的简介视频，详细了解课程目标和要求。如需了解您的计算机是否可以下载 Android Studio，请访问 https://developer.android.com/studio ， 在此页面底部查看系统要求

## 3. 使用 Kotlin 编写您的第一个程序
> 使用 Kotlin 创建您的第一个程序。

### 1. 准备工作
   > 在此 Codelab 中，您将借助一款可在浏览器中运行的交互式编辑器，使用 Kotlin 语言编写您的第一个程序。

   > 您可以将程序视为一系列指示系统执行某项操作的指令。举例而言，您可以编写一个用于制作生日贺卡的程序。在该程序中，您可以编写一条指令，指示系统输出祝福语，或根据寿星的出生年份计算其年龄。

   > 就像您使用人类语言与他人沟通一样，您可以使用编程语言与计算机的操作系统进行沟通。幸运的是，相较于人类语言，编程语言更简单，逻辑相当严密。

   > Android 应用采用 Kotlin 编程语言编写。Kotlin 是一种现代语言，旨在帮助开发者高效编写代码，并尽可能减少错误。

   > 同时学习如何创建应用和编程基础知识并非易事，因此，我们将先介绍一些编程的入门知识，然后再讲解如何创建应用。先熟悉一些编程基础知识，这不仅是创建应用的重要步骤，还有助于您在本课程中的后面部分，更轻松地创建您的第一款应用。

   > 代码编辑器是帮助您编写代码的工具，这和文字处理器（如 Google 文档）帮助您创建文本文档是一样的。在此 Codelab 中，您将在浏览器中使用交互式 Kotlin 编辑器。这意味着，您不必安装任何软件，即可迈出应用开发的第一步。

#### 前提条件
- 能在网络浏览器中使用交互式网站。
#### 学习内容
- 如何创建、更改、理解和运行用于显示一条消息的最简单的 Kotlin 程序。
#### 您将构建的内容
- 您将使用 Kotlin 编程语言编写一个在运行时将显示一条消息的程序。
#### 所需条件
- 一台安装了新版网络浏览器（如最新版 Chrome）的计算机。
- 计算机可以访问互联网。

### 2. 运行您用 Kotlin 编写的第一个程序
在此任务中，您将使用网站上的编辑器，立即上手 Kotlin 语言编程。

使用交互式代码编辑器

您可以不必在计算机上安装软件，而是使用网页版工具来创建您的第一个程序。

1. 在浏览器中，打开 https://developer.android.com/training/kotlinplayground 。这将打开一个基于浏览器的编程工具。
2. 您应该会看到一个类似于以下屏幕截图所示的页面，页面中间便是一个代码编辑器。
![makekdown](https://developer.android.google.cn/codelabs/basic-android-kotlin-training-first-kotlin-program/img/c76b631b5d7b5546.png)
以下是编辑器中的程序代码：
```
fun main() {
    println("Hello, world!")
}
```
运行程序代码  
运行您创建的程序与在计算机上运行文字处理器等程序没有多大区别。不同之处在于，在您运行程序来处理事务或玩游戏时，您关注的是程序的功能，而不是实现功能的代码。在编程过程中，您能查看并处理实现这些神奇功能的实际代码。

我们来看看这个程序能做什么！
1. 在编辑器的右上角，找到白色或绿色三角形图标![makedown](https://developer.android.google.cn/codelabs/basic-android-kotlin-training-first-kotlin-program/img/3384088a105a0da9.png)，点击它即可运行程序。
2. 查看屏幕底部的窗格。  
` Hello, world! `
3. 您可以看到，系统输出了 `Hello, world!`，如上图所示。现在您应该知道这个程序的作用了：它输出一条 Hello World 的消息。
“编译”是将 Kotlin 程序代码转换为系统可运行的形式的过程。如果编译成功，则表明程序中没有会阻碍其正常运行的错误。如果有问题，它们会显示在屏幕底部的窗格中。