# 在Unity3D中使用设计模式

[Engligh](README-EN.md)

这个仓库是在Unity3D中实现设计模式的合集，使用C#编写。

- 包含GOF的23种设计模式
- 包含《游戏编程模式》的Unity实现

设计模式非常棒。许多的设计模式单单是看起来就很精妙，但对于部分人（起码对于初学时地我）而言，最大的困扰是：

- 我不知道设计模式的用途是什么以及什么时候使用它。
- 我曾今都学过他们，但工作后我基本都忘掉了。
- 我应该都使用过，但我想看看别人（尤其是一些好的项目的源代码）是如何使用它的。

所以**我尝试用一个全新的形式来学习和解释设计模式**：

我把设计模式分为两类，他们分别是：

1. 一些使用不那么广泛的设计模式，你应该听过他们的名字，但就是不清楚什么时候该使用它——它离使用太遥远了

2. 一些使用非常广泛的设计模式，你应该用过，但就是想再深入看看Unity引擎在哪些地方用了这个设计模式。（如单例，原型等）

对于第一种情况。
在介绍设计模式前，我会先抛出一个问题：

**如果抛开所有的设计模式，你会如何实现某一个功能？**

**这个需求会是游戏开发领域内的具体的需求，而非是很多书或者示例里提的空泛的概念**

**这非常重要，我受够了各种在餐厅里点单，复制一个动物,Square和Cirle继承Shape,MyShapeFactory等的例子。他们为什么就不能是一个游戏领域内的例子呢？**

然后我会给出坏代码和使用了设计模式的好代码，来帮助更好地理解设计模式。

希望这种形式能帮助你更好地理解设计模式。

对于第二种情况。

**我会着重如何在Unity里使用它[UnityCSReference](https://github.com/Unity-Technologies/UnityCsReference)(Unity的C#的部分源码)里是怎么使用它的。**

建议配合一本参考资料里列出的书一起看，然后再动手自己写一遍代码。

希望这能帮助到你们！

---

## 每个部分包含哪些内容？

### Brief

设计模式的基本介绍。

### The Question

需求（我会尽量让这个需求更接近于真实需求）是什么？

### Bad Code Example

抛开脑子里关于模式的认知，想想你会怎么写？
以及一个错误的示例。

### Good Code Example

使用设计模式实现这个需求的代码示例。

### (可能会有) Let's see the source code

[UnityCSReference](https://github.com/Unity-Technologies/UnityCsReference)里的源码

### Post
一个我的博客文章的链接，里面会包含代码的详细解释和更多细节。

---

## 内容

目前已经完成的例子有：

**创建型模式**
- [x] [工厂方法模式](./Assets/CreationalPatterns/FactoryMethod/README.md)
- [x] [抽象工厂模式](./Assets/CreationalPatterns/AbstractFactory/README.md)
- [x] [建造者模式](./Assets/CreationalPatterns/BuilderPattern/README.md)
- [x] [原型模式](./Assets/CreationalPatterns/Prototype/README.md)
- [x] [单例模式](./Assets/CreationalPatterns/Singleton/README.md)


**行为型模式**
- [] Chain Of Responsibility
- [] Command
- [] Iterator
- [] Mediator
- [] Memento
- [x] [观察者模式](./Assets/BehavioralPattern/Observer/README.md)
- [] State
- [] Strategy
- [] Template Method
- [] Visitor

**结构型模式**
- [] Adapter
- [] Bridge
- [] Composite
- [] Decorator
- [] Facade
- [x] [享元模式](./Assets/StructuralPattern/Flyweight/README.md)
- [] Proxy


## 致谢

本项目参考了以下项目的部分代码：
- [Habrador/Unity-Programming-Patterns](https://github.com/Habrador/Unity-Programming-Patterns)
- [QianMo/Unity-Design-Pattern](https://github.com/QianMo/Unity-Design-Pattern)
向他们表示衷心的感谢！

## 参考资料与了解更多

- [Game Programming Patterns](http://gameprogrammingpatterns.com/)

- [Refactoring.Guru](https://refactoringguru.cn/)

- [C#设计模式（第2版） (豆瓣) (douban.com)](https://book.douban.com/subject/30131470/)

- [设计模式与游戏完美开发 (豆瓣) (douban.com)](https://book.douban.com/subject/26952185/)

- [Habrador/Unity-Programming-Patterns](https://github.com/Habrador/Unity-Programming-Patterns)

- [QianMo/Unity-Design-Pattern](https://github.com/QianMo/Unity-Design-Pattern)

- [UnityCSReference](https://github.com/Unity-Technologies/UnityCsReference)

- [.NET Framework](https://referencesource.microsoft.com/)

## License

本工程使用[MIT授权协议](https://opensource.org/licenses/MIT)。

参考了一些外部工程的源码，查看[License](./LICENSE)以获取全部的授权文本。