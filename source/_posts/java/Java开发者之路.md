---
title: 需要掌握哪些东西才能找到一份初级Java的工作？
---

# 需要掌握哪些东西才能找到一份初级Java的工作？

**Java初学者需要掌握哪些技能才能找到一份初级Java的工作，或者说有资格去一家好的公司中当实习生？需要学习哪些工具？哪些技术？**

**这些问题没有一个标准的答案。 一些大公司更倾向于找基础扎实，学习能力强，潜力大的学霸。一些小公司创业公司更倾向于找一些有实战经验、前端后端运维什么都会一些的多面手。**

### 首先就是Java核心技术

##### java语法

Java核心技术指Java语言基础，也称作JavaSE，主要包含了以下概念：

- 类、变量、方法
- 八种基础数据类型（byte、char、short、int、long、float、double、boolean）
- 字符串
- 基础的运算符、关键字
- 基础的结构：循环、条件、代码块

这些是基础的基础，每个初学者都必须掌握。

##### 面向对象的概念（OOP，Object-oriented programming）

- 封装；隐藏对象的属性和实现细节，仅对外提供公共访问方式，将变化隔离，便于使用，提高复用性和安全性。
- 继承；提高代码复用性；继承是多态的前提。
- 多态；父类或接口定义的引用变量可以指向子类或具体实现类的实例对象。提高了程序的拓展性。

##### 集合框架

集合就是把一些对象装在一起的一个**容器** ，掌握基础的数据结构能更好的理解Java的集合，Java的集合主要包含以下组件：

- `List`
- `Set`
- `Map`
- `ArrayList`
- `LinkedList`
- `Queue`
- `Deque`
- `HashSet`, `HashMap`, `HashTable`
- `TreeSet`, `TreeMap`

其中比较常用，且会在面试中问到的有 ```ArrayList``` 、`LinkedList ` 、`HashSet`、 `HashMap` `HashTable`、`ConcurrentHashMap`，这些都是需要知道其原理的。

##### 异常处理

异常是在执行程序时可能会发生的异常情况。 所有异常类都是`java.lang.Exception`类的子类型。

- 异常处理机制
- Try-catch-finally
- `throw`, `throws`区别，使用场景
- 异常的继承关系
- Checked/unchecked exceptions
- `Error` 和 `Exception` 的区别
- 手动抛出异常
- 常见的异常，`NullPointerException` `ArrayIndexOutOfBoundsException` `IOException`等等

##### 输入/输出流（Input/Output）

- 读取文件、写文件
- 读取http请求、写http请求

##### 多线程、并发

比较困难的Java核心主题，几乎所有初学者都在理解和使用多线程方面遇到困难，但是，掌握了多线程是通往高级Java工程师的必经之路。

- 线程的生命周期 (new, runnable, waiting, timed waiting, terminated)
- `Runable` `Thread` 的区别
- 线程同步
- 死锁产生的原理和如何避免
- 线程中断（interrupt）
- `Wait`, `notify`, `notifyAll`
- `Sleep`, `yield`, `join`
- `volatile` 引申来的内存模型，原子性、可见性

##### Lambda 表达式

Lambda表达式是Java8的新东西，现在已经Java15了，所以你应该学习并掌握它。

对于初学者来说Lambda表达式和多线程是两个比较难掌握的知识点，但是如果你掌握了，那将成为你找工作的优势。其他条件都相同，你掌握了这些，那面试官肯定选你而不是其他人。

### 算法和数据结构

面试前先来两道算法开胃已经成了基本操作，不想三分钟结束面试，那你多少要能手写一些基本的排序、查找算法，数据结构数组、树、栈和队列、哈希表这些的原理也要说得上来。

### Java高级

- servlet，Java程序与网页通讯的基础
- JDBC，Java操作数据库

### 框架

- Spring，企业开发的必备技能，至少要知道这是个什么东西，用来做什么，熟悉常见的注解
- SpringMVC，web应用的核心
- SpringBoot，微服务
- Mybatis，知道如何写mapper

### 其他工具和语言

- maven/gradle
- git
- sql
- 前端
  - html
  - css
  - JavaScript

### 总结

看起来有点吓人？ 如果你喜欢编程，对技术感兴趣并且决心成为一名程序员，那就不必担心。 一步一步地学习、实战，这些技能3-4个月就能掌握。等到某天你成为公司的核心工程师，熟稔分布式、高并发、架构设计，回过头来看这些会觉得不过如此。




