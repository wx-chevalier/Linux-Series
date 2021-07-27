![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg) ![](https://parg.co/bDm)

# Linux 实践笔记

操作系统是管理计算机硬件与软件资源的计算机程序，同时也是计算机系统的内核与基石。计算机系统由硬件和软件两部分组成。操作系统 (OS，Operating System) 是配置在计算机硬件上的第一层软件，是对硬件系统的首次扩充。它在计算机系统中占据了特别重要的地位；而其它的诸如汇编程序、编译程序、数据库管理系统等系统软件，以及大量的应用软件，都将依赖于操作系统的支持，取得它的服务。以 Intel Pentium 系统产品系列的模型为例：

![image](https://user-images.githubusercontent.com/5803001/52262868-a8646480-2968-11e9-963e-c91128a6fe2c.png)

操作系统已成为现代计算机系统（大、中、小及微型机）、多处理机系统、计算机网络、多媒体系统以及嵌入式系统中都必须配置的、最重要的系统软件。从一般用户的观点，可把 OS 看做是用户与计算机硬件系统之间的接口；从资源管理的观点看，则可把 OS 视为计算机系统资源的管理者。另外，OS 实现了对计算机资源的抽象，隐藏了对硬件操作的细节，使用户能更方便地使用机器。

# 操作系统的作用

## 用户与计算机硬件系统之间的接口

OS 处于用户与计算机硬件系统之间，用户通过 OS 来使用计算机系统。或者说，用户在 OS 帮助下，能够方便、快捷、安全、可靠地操纵计算机硬件和运行自己的程序。

用户可以通过如下三种方式使用操作系统

- 命令方式。这是指由 OS 提供了一组联机命令接口，以允许用户通过键盘输入有关命令来取得操作系统的服务，并控制用户程序的运行。
- 系统调用方式。OS 提供了一组系统调用，用户可在自己的应用程序中通过相应的系统调用，来实现与操作系统的通信，并取得它的服务。
- 图形、窗口方式。这是当前使用最为方便、最为广泛的接口，它允许用户通过屏幕上的窗口和图标来实现与操作系统的通信，并取得它的服务。

## 计算机系统资源的管理者

在一个计算机系统中，通常都含有各种各样的硬件和软件资源。归纳起来可将资源分为四类：处理器、存储器、IO 设备以及信息 ( 数据和程序 )。相应地，OS 的主要功能也正是针对这四类资源进行有效的管理，即：处理机管理，用于分配和控制处理机；存储器管理，主要负责内存的分配与回收；IO 设备管理，负责 IO 设备的分配与操纵；文件管理，负责文件的存取、共享和保护。可见，OS 的确是计算机系统资源的管理者。事实上，当今世界上广为流行的一个关于 OS 作用的观点，正是把 OS 作为计算机系统的资源管理者。

## 计算机资源的抽象

对于一个完全无软件的计算机系统（即裸机），它向用户提供的是实际硬件接口（物理接口），用户必须对物理接口的实现细节有充分的了解，并利用机器指令进行编程，因此该物理机器必定是难以使用的。为了方便用户使用 IO 设备，人们在裸机上覆盖上一层 IO 设备管理软件，由它来实现对 IO 设备操作的细节，并向上提供一组 IO 操作命令，如 Read 和 Write 命令，用户可利用它来进行数据输入或输出，而无需关心 IO 是如何实现的。此时用户所看到的机器将是一台比裸机功能更强、使用更方便的机器。这就是说，在裸机上铺设的 IO 软件隐藏了对 IO 设备操作的具体细节，向上提供了一组抽象的 IO 设备。

# About

## Copyright & More | 延伸阅读

笔者所有文章遵循 [知识共享 署名-非商业性使用-禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)，欢迎转载，尊重版权。您还可以前往 [NGTE Books](https://ng-tech.icu/books/) 主页浏览包含知识体系、编程语言、软件工程、模式与架构、Web 与大前端、服务端开发实践与工程架构、分布式基础架构、人工智能与深度学习、产品运营与创业等多类目的书籍列表：

[![NGTE Books](https://s2.ax1x.com/2020/01/18/19uXtI.png)](https://ng-tech.icu/books/)
