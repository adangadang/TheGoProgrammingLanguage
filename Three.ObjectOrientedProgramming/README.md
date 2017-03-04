### 第3章 面向对象编程
在第2章中，详细介绍了Go语言顺序编程的相关特性，通过与C语言的对比了解了为什么Go语言被称为"更好的C语言"，本章将介绍Go语言对于面向对象编程(`OOP`,Object Oriented Progamming)思想的支持。相应地，本章在介绍Go语言的面向对象编程特性的过程中，对比对象会自然切换为比较典型的现有面向对象编程语言：C++、Java和C#。

为了加深读者对Go语言面向对象特性的理解，本章中会提及C++、Java和C#语言的一些特性和例子。如果读者之前没有接触过这些语言，阅读本章并不会有明显的障碍。但如果之前深入了解过这几门语言或者其他的面向对象语言，那么会更清晰的理解Go语言相对于C++流派的面向对象体系的众多革新之处。

对于面向对象编程的支持Go语言设计的非常简洁而优雅。简洁之处在于，Go语言并没有沿袭传统面向对象编程中的诸多概念，比如继承、虚函数、构造函数、和析构函数、隐藏的this指针等。优雅之处在于，Go语言对面向对象编程的支持是语言类型系统中的天然组成成分。整个类型系统通过接口串联，浑然一体。将在本章中一一解释这些特性。