---
title: Object Oriented Programming (OOP)
localeTitle: 面向对象编程（OOP）
---
## 大纲

*   为什么面向对象（以下简称为OO）？
*   OO概念
*   接下来是什么？

## 为何选择OO？

在这个范例中，实体被表示为真实世界数据。例如，我们想要代表一只狗。在OO范例中，我们只创建一个名为“dog”的类，并赋予它属性（颜色，年龄，性别等）和行为（树皮，跑步，吃饭等）。行为通过改变属性的“方法”（简单的函数）来改变。

## OO概念

OO编程的强大之处在于它能够执行以下操作：

*   传承
*   多态性
*   封装
*   抽象化

在过程编程中，我们只需创建变量并在需要时更改它们。但是在面向对象编程中，我们可以从字面上模拟真实世界的对象。通过为实体（例如dog）创建特定类来实现封装。然后创建此类的对象，这些对象只是类的实例。每个对象都有自己的属性值。

另一个非常有用的概念是继承。这个想法是一个类可以从基类继承属性和行为。例如，在创建游戏时，我们有一个玩家和敌人。我们可以创建一个名为person的基类，并为其赋予名称，年龄，性别等属性。人的行为可以是步行和跳跃。然后玩家和敌人可以从人身上继承这些“品质”，并且可以增加诸如杀戮，得分，吃饭等品质。

这有助于重用代码并使rcode结构更加干净。数据隐藏是另一个很酷的功能。在OO中，我们有私有和公共属性的概念。私有属性只能通过该特定类的方法进行访问和修改，而公共数据可以从程序中的任何位置进行修改（显然在范围内）。

## 接下来是什么？

选择一种OO语言，并构建一个基于终端的基本游戏来说明这些概念。