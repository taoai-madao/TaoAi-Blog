---
title: 刷题知识点Spring篇
tags:
  - Spring
  - 刷题
  - 面试题
data: 2023-09-27 18:13:33
copyright_author: taoai-madao
copyright_author_href: https://github.com/taoai-madao
copyright_url: http://www.taoaimadao.top/
copyright_info: 此文章信息来源于网络，本人只做总结使用
---
# 刷题知识点Spring篇
## Spring家族体系
```Text
Spring Core --> SpringMVC
Spring Data --> 数据访问
Spring Boot --> 多封装即用组件，便于开发
Spring Cloud --> 云服务
```
## 什么是 Spring 框架
```Text
Spring框架是用于快速构建企业级Java应用程序的开源框架。它提供了一种综合性的编程和配置模型，便于开发人员
快速开发灵活、可扩展、可维护的企业级应用程序

Spring框架的核心特点
  1. 轻量级：Spring 框架采用了松耦合的设计原则，仅依赖于少量的第三方库，因此它是一个轻量级的框架。开
     发人员可以根据需要选择使用 Spring 的特定功能，而无需引入整个框架。
  2. 控制反转（IoC）：Spring 框架通过控制反转（IoC）容器管理应用程序中的对象及其依赖关系。通过IoC容
     器，开发人员可以将对象的创建、组装和生命周期管理交给 Spring 框架处理，从而实现了松耦合和可测试性。
  3. 面向切面编程（AOP）：Spring 框架支持面向切面编程，可以通过 AOP 在应用程序中实现横切关注点的模块
     化。例如，日志记录、事务管理和安全性等横切关注点可以通过 AOP 进行集中处理而不会侵入业务逻辑的代码。
  4. 声明式事务管理：Spring 框架提供了声明式事务管理的支持。通过使用注解或 XML 配置，开发人员可以将事
     务管理逻辑与业务逻辑分离，并且可以轻松地在方法或类级别上应用事务。
  5. 框架整合：Spring 框架可以与许多其他开源框架和技术无缝集成，如 Hibernate、MyBatis、JPA、Struts
     和 JSF 等。这使得开发人员可以使用 Spring 框架来整合和协调不同的技术，构建全面的企业应用程序。
  6. 测试支持：Spring 框架提供了广泛的测试支持，包括单元测试和集成测试。它提供了一个专门的测试上下文，可
     以轻松地编写和执行单元测试，以验证应用程序的行为和功能。
```
## 什么是IoC（Inversion of Control 控制反转）
```Text

```
