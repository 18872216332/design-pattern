### Design Pattern

##### 原则
- 单一职责原则，就一个类而言，应该仅有一个引起它变化的原因
- 开放-封闭原则，软件实体（类、模块、函数等等）可以扩展，但是不可以修改
- 依赖倒转原则，高层模块不应该依赖低层模块，都应该依赖抽象。抽象不应该依赖细节，细节应该依赖抽象
- 里氏代换原则，子类必须能替换掉它们的父类型
- 迪米特法则，也叫最少知识原则，如果两个类不必彼此直接通信，那么这两个类就不应当发生直接的相互作用。如果其中一个类需要调用另一个类的某一个方法的话，可以通过第三者转发这个调用

##### 设计模式种类
* [简单工厂模式(Simple Factory)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/simplefactory)

* 抽象工厂模式(Abstract Factory)

* [策略模式(Strategy)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/strategy), 
它定义了算法家族，分别封装起来，让它们之间可以相互替换，此模式让算法的变化，不会影响到使用算法的客户。

* [装饰模式(Decorator)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/decorator), 
动态地给一个对象添加一些额外的职责，就增加功能来说，装饰模式比生成子类更为灵活。

* [代理模式(Proxy)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/proxy), 
为其他对象提供一种代理以控制对这个对象的访问。

* [工厂方法模式(Factory Method)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/factorymethod), 
定义一个用于创建对象的接口，让子类决定实例化哪一个类。工厂方法使一个类的实例化延迟到它的子类。

* [原型模式(Prototype)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/prototype), 
用原型实例指定创建对象的种类，并且通过拷贝这些原型创建新的对象。

* [模板方法模式(Template Method)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/templatemethod), 
定义一个操作中的算法骨架，而将一些步骤延迟到子类中。模板方法使得子类可以不改变一个算法的结构即可以重定义该算法的某些特定步骤。

* [外观模式(Facade)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/facade), 
又叫门面模式，为子系统中的一组接口提供一个一致的界面，此模式定义了一个高层接口，这个接口使得这一子系统更加容易使用。

* [建造者模式(Builder)](https://github.com/ToryZhou/design-pattern/tree/master/src/main/java/com/job/designpattern/builder), 
又叫生成器模式，将一个复杂对象的构建与它的表示分离，使得同样的构建过程可以创建不同的表示。

```
说明：UML类图使用 Idea PlantUML plugin
```