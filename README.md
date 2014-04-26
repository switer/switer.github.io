switer.github.io
================

Personal homepage

Web Component
-------------
* [web component](https://github.com/switer/switer.github.io/issues/6)
* [使用component规范的组件模块划分](https://github.com/switer/switer.github.io/issues/3)

About MVVM Framework
--------------------
* [Ractive与Vue的比较](https://github.com/switer/switer.github.io/issues/5)
* [vue与ripple的比较](https://github.com/switer/switer.github.io/issues/4)

Developer Principles
--------------------
* [软件开发成功 12 法则](https://github.com/switer/switer.github.io/issues/2)
* [抽象泄露法则](https://github.com/switer/switer.github.io/issues/1)


Other
-----

### Data binding

Two way to implement data-binding of mvvm

#### change-listener (KO, ember)

* 强制继承指定的类和使用访问器去访问数据属性，使语法变得残暴！！


#### dirty-checking (angular)

 

### Module pattern

#### 独立与本地化

Module Pattern的优点

1. 可伸缩性 scalable
    模块可以灵活插拔

2. 为团队准备的 term-ready
    团队成员可以独立维护不同的模块，并行开发

3. 局部性的 localized


4. 跨实例的私有对象
    模块类生成的使用可以共享module内的私有对象

5. 可扩展性

6. 可延时加载


一个well-design的Module Pattern

1. 不要让模块间有明确的依赖关系，每个模块的使用范围仅限于模块内或模块间共享的插件

2. 使用观察者模式（pub/sub）进行模块间的通信，不可以直接调用模块（同一层级）

3. 创建一个轻量综合的层去管理模块的注入与交互
