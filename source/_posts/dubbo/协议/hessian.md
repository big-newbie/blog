---
title: dubbo hessian 协议
---

- http 通讯
- Servlet 暴露服务
- 默认内嵌 Jetty 作为服务器

## 特性
 - 连接个数：多连接
 - 连接方式：短连接
 - 传输协议：HTTP
 - 传输方式：同步传输
 - 序列化：Hessian
 - 适用范围：**传入传出数据包较大**，**提供者比消费者多**，**提供者压力较大**，**可传文件**
 - 适用场景：**页面传输，文件传输**

## 约束

- 参数及返回值需实现`Serializable`接口
- 参数及返回值不能自定义实现`List`，`Map`，`Number`，`Date`，`Calendar`等接口，只能用 JDK 自带显示，因为 hessian 会做特殊处理，**自定义实现类的属性值都会丢失**

## 依赖

```xml
    <dependency>
        <groupId>com.caucho</groupId>
        <artifactId>hessian</artifactId>
        <version>4.0.51</version>
    </dependency>

    <dependency>
        <groupId>org.mortbay.jetty</groupId>
        <artifactId>jetty</artifactId>
        <version>6.1.26</version>
    </dependency>
```

