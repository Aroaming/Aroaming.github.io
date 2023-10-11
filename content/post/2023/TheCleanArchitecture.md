---
title: "TheCleanArchitecture"
date: 2023-09-18T11:50:51+08:00
draft: true
---

# The Clean Architecture

对于一个合适的框架，应该是划分明确，顺序依赖。

![image-20230918114702529](post/2023/img/clean.png)

Each of these architectures produce systems that are:

1. Independent of Frameworks. The architecture does not depend on the existence of some library of feature laden software. This allows you to use such frameworks as tools, rather than having to cram your system into their limited constraints.
2. Testable. The business rules can be tested without the UI, Database, Web Server, or any other external element.
3. Independent of UI. The UI can change easily, without changing the rest of the system. A Web UI could be replaced with a console UI, for example, without changing the business rules.
4. Independent of Database. You can swap out Oracle or SQL Server, for Mongo, BigTable, CouchDB, or something else. Your business rules are not bound to the database.
5. Independent of any external agency. In fact your business rules simply don’t know anything at all about the outside world.

我们知道在设计干净的体系结构之前的约束是:  
  
1、独立于框架。该体系结构不依赖于某些功能丰富的软件库的存在。这允许您使用这样的框架作为工具，而不必将您的系统塞进它们的有限约束中.  
2、可测试的。业务规则可以在没有 UI, 数据库，Web 服务器或任何其他外部元素的情况下进行测试.  
3、独立于用户界面。用户界面可以很容易地更改，而不必更改系统的其他部分。例如，Web 用户界面可以替换为控制台用户界面，而不必更改业务规则.  
4、独立于数据库。您可以将 Oracle 或 SQL Server 换成 Mongo, BigTable, CouchDB 或其他东西。您的业务规则未绑定到数据库.  
5、独立于任何外部机构。实际上，您的业务规则根本不了解外部世界.  



参考：

1、[The Clean Code Blog](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

2、[分享一个干净简洁的 Golang 项目架构](https://learnku.com/go/t/43569)

3、[Go 面向包的设计和架构分层](https://github.com/danceyoung/paper-code/blob/master/package-oriented-design/packageorienteddesign.md)

4、[go-clean-arch](https://github.com/bxcodec/go-clean-arch/tree/master)

