---
title: C语言
---

---

C语言是最接近[[汇编语言]]的高级语言之一，在引入大量先进编程思想和特性的同时，保证了**所有逻辑和特性都对应着特定的一种或一类汇编语言逻辑**。可以说，写C代码相当于以一种更舒服的姿势写汇编。

这一特点的好处是，C拥有几乎等同于汇编的极高灵活性，这让程序员能对系统做出更加精细可控、粒度更高的操作。这让C广泛应用于对性能高度敏感的领域，比如高速硬件（GPU、网卡、硬盘...）的驱动、操作系统内核、单片机编程、游戏引擎、超大规模计算等。

---

坏处是，**C并不适合编程入门。**

这并不能怪C。C的设计初衷本来就是汇编++，它面向的群体是对计算机运行原理有相当了解的专业程序员，也只有他们需要C提供的高灵活性。

**但是，学编程$\ne$学计算机。** 

随着现代高级语言的发展，以及各领域软件生态的建立，非计算机科班的群体学习编程的需求已经不可忽视。它们使用编程的场景，无外乎科学计算、数据分析、爬虫、办公自动化这些对性能几乎没有要求的场景，只需要对变量、分支循环、函数调用的概念有基本了解，再学会Google对应的库或者现成的代码，就基本可以应付了。

然而，**仅仅学习分支循环这点东西，是不需要任何有关计算机运行原理的前置知识的**，只要把计算机想象成一个能操作文件、能为每个名字的变量分配一个装数据的盒子、能读懂用特定格式编写的逻辑并精准执行的神奇黑盒就行了。

关键是，即便简化到这个程度，**即使只有赋值运算分支循环调包这几个单拎出来没有任何理解障碍的东西，都蕴含着爆炸式增长的无限可能性。无数深耕于高度细分的应用领域的软硬件工程师，用着这么“简单”的东西干了一辈子活，都不敢说自己玩明白了。**

这才是编程入门需要专注于的东西。

因此，**非科班群体完全不需要C语言带来的好处，却由于C语言过于精细、过于贴近计算机底层的特点，他们在学习C语言不得不将面临大量对非科班群体极其不友好的东西**，比如指针、结构体，比如“编译”的概念，比如“为什么我写的程序只能在小黑框里跑”。

对于修过计算机组成原理的科班学生，这些东西属于一看就懂，也许看懂之余还会赞叹一句“哇这个设计不错”；而非科班群体则将面临额外的思维负担，而且由于相当一部分人（包括科班）的编程入门学习资料水准一言难尽，这部分思维负担将比本应有的还要大得多。

此外，C拉胯的软件生态，进一步提高了C学习者将编程用于生产实践的门槛，“只能在小黑框里跑”带来的“这玩意能有啥用”的想法更是催生了不小的枯燥、无意义感，这在一门技能的入门阶段是致命的。

# 如何学习C
如果你属于上面提到的非科班人群，