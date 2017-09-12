# 设计模式（Design Parttern）
我要正儿八经的弄懂设计模式。这是开始，先搞明白的什么是设计模式。
## 定义
设计模式是一套被 **反复使用**、**多数人知晓**、**经过分类编目的**、**代码设计经验的总结**。
## 为什么要用设计模式
为了 **可重用** 代码，让代码更容易的被他人理解并保证代码的 **可靠性**。
## 谁这么叼设计牛模式
四人组( Gang of Four )，简称 GoF ,分别是 **Erich Gamma**, **Richard Helm **, **Ralph Johnson **和 **John Vlissides** 。但不是他们设计的，是他们在 95年的时候整理归纳 23 种最常用的设计模式并会变成一本书 **Design Patterns: Elements of Reusable Object-Oriented Software** 就是：《设计模式：可复用面向对象软件的基础》 。是经过时间的验证的，大家一定要学会。
## 怎么学
balabala ... <br>
> 设计模式最重要的 4 个元素 **模式名称 (Parttern Name)**、 **问题(Problem)** 、 **解决方案 (Solution)** 、 **效果 (Consequences)**。<br>
学习设计模式我们就从这 4 个元素出发。一个一个弄清楚它。

- **模式名称 (Parttern Name)**
<br>就是这个模式的名字。简单明了的命名。
- **问题 (Problem)**
<br>描述了应该在何时使用模式，它包含了设计中存在的问题以及问题存在的原因
- **解决方案 (Solution)**
<br>该框架的解决方案。就是如何设计这个模式。描述了一个设计模式的组成成分，以及这些组成成分之间的相互关系，各自的职责和协作方式，通常解决方案通过UML类图和核心代码来进行描述。
- **效果 (Consequences)**
<br>描述了模式的优缺点以及在使用模式时应权衡的问题 (呈现)
## 说到这里，你都有啥框架
我们要掌握的应该除了GoF 说的 23 种模式还有加一个 简单工厂模式 （Simple Factory Pattern）也很常用还简单。我顺手就学会了。

来个预览先（[参考]）
<table style="WIDTH: 673px; HEIGHT: 1441px" align="center" cellspacing="0" cellpadding="0" border="1"><tbody><tr><td style="BACKGROUND: rgb(242,242,242)" valign="top"><p align="center"><strong><span style="FONT-SIZE: 16px"><span style="font-size:18px;">类型</span></span></strong></p></td><td style="BACKGROUND: rgb(242,242,242)" valign="top"><p align="center"><strong><span style="FONT-SIZE: 16px"><span style="font-size:18px;">模式名称</span></span></strong></p></td><td style="BACKGROUND: rgb(242,242,242)" valign="top"><p align="center"><strong><span style="FONT-SIZE: 16px"><span style="font-size:18px;">学习难度</span></span></strong></p></td><td style="BACKGROUND: rgb(242,242,242)" valign="top"><p align="center"><strong><span style="FONT-SIZE: 16px"><span style="font-size:18px;">使用频率</span></span></strong></p></td></tr><tr><td rowspan="6"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">创建型模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Creational Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">单例模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Singleton Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★☆☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">简单工厂模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Simple Factory Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">工厂方法模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Factory Method Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★★</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">抽象工厂模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Abstract&nbsp; Factory Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★★</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">原型模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Prototype Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">建造者模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Builder Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td></tr><tr><td rowspan="7"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">结构型模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Structural Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">适配器模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Adapter Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">桥接模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Bridge&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">组合模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Composite&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">装饰模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Decorator&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">外观模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Façade&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★☆☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★★</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">享元模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Flyweight&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★☆☆☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">代理模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Proxy&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td></tr><tr><td rowspan="11"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">行为型模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Behavioral Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">职责链模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Chain&nbsp; of Responsibility Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">命令模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Command&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">解释器模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Interpreter&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★★</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★☆☆☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">迭代器模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Iterator&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★★</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">中介者模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Mediator&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">备忘录模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Memento&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">观察者模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Observer&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★★</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">状态模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">State&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">策略模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Strategy&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★☆☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">模板方法模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Template&nbsp; Method Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★☆☆☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★☆☆</span></span></p></td></tr><tr><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;">访问者模式</span></span></p><p align="center"><span style="font-family:Times New Roman;font-size:18px;">Visitor&nbsp; Pattern</span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★★★★☆</span></span></p></td><td valign="top"><p align="center"><span style="FONT-SIZE: 16px"><span style="font-size:18px;color:#ff0000;">★☆☆☆☆</span></span></p></td></tr></tbody></table>
<br>

看图得知，这是按照用途分为三种： **创建型（Creational**, **结构型（Structural**, **行为型（Behavioral** 三种。
接下来就按照表格 模式名称这一列顺序一一讲解。学习难度和使用频率并不重要，因为我都要会。

[参考]: http://blog.csdn.net/LoveLion/article/details/7420863
