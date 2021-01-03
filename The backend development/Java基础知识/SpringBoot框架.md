# Spring Boot 框架

## 1. Spring Boot的概述

Spring框架是java平台的一种开源框架，他为开发者提供了一系列的解决方案，比如控制反转（Ioc）的特性将对象统一管理；利用面向切面编程（AOP）的特性可以对业务的各个部门进行隔离，降低业务模块之间的耦合度。

- Spring核心特性：
  1. IOC
  2. AOP

## 2.Spring Boot 解决的问题

1. 使编码变得简单
2. 使配置变得简单
3. 使部署变得简单
4. 使监控变得简单

## 3. Spring boot 核心机制

- Spring boot 主要有四大核心机制：
  1. auto—configuration:针对很多常见的Spring应用程序的常见的应用功能，Spring Boot能自动提供相关的配置。
  2. Starter依赖：Spring Boot需要什么功能他就导入响应的库。
  3. Spring Boot CLI：(可选)：主要针对Groovy,简化了开发流程。
  4. Spring Boot Actuator:能够深入运行中的springboot应用程序，监控程序内部的各个信息。

## 4. Spring Boot的优缺点

1. 优点

   1. 能够快速创建独立运行的Spring项目并与主流框架集成
   2. 使用嵌入式的servlet容器，无需打包成war包，直接通过main方法启动
   3. 提供了starter pom,能够非常方便的对jar包进行管理，简化了maven的配置
   4. 大量的自动配置，简化了开发。
   5. 无需配置XML,采用注解自动配置
   6. 提供了程序的监控
   7. 与云计算天然集成

2. 缺点

   1. 集成度太高，不知道底层实现
   2. 配置比较少，报错时很难定位

   