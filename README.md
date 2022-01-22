# DesignPattern
# 设计模式学习


## 1.设计原则:
    - 单一职责原则(Single Responsibility Principle)
        一个类应该只有一个发生变化的原因, 就是说每个类只需要负责自己的那部分功能, 类的复杂度就会降低
    - 开闭原则(Open Closed Principle)
        例如 js中模块和函数应该对扩展开放，对修改开放
    - 里氏替换原则(Liskov Substitution Principle)
        所有引用基类的地方必须能透明地使用其子类对象, 也就是说子类对象可以替换父类对象, 而程序执行效果不变
    - 迪米特法则(Law of Demeter)
        又叫作最少知识原则(The Least Knowledge Principle), 一个类对于其他类知道的越少越好, 就是说一个对象应对其他对象有尽可能少点了解
    - 接口隔离原则(Interface Segregation Principle) flow ts
        多个特定的客服端接口要好于一个通用性的总接口
    - 依赖倒置原则(Dependence Inversion Principle)
        1. 上层模块不应该依赖底层模块, 它们都应该依赖于抽象
        2. 抽象不应该依赖于细节, 细节应该依赖于抽象

## 2.设计模式
    - 单例模式
        优点: 节约开销，例如弹窗等
        缺点: 扩展性太差