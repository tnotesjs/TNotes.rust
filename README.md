# rust

<!-- region:toc -->

- [1. TNotes.rust](#1-tnotesrust)
- [2. 入门指南](#2-入门指南)
- [3. 编写一个猜数字游戏](#3-编写一个猜数字游戏)
- [4. 常见编程概念](#4-常见编程概念)
- [5. 认识所有权](#5-认识所有权)
- [6. 使用结构体组织相关联的数据](#6-使用结构体组织相关联的数据)
- [7. 枚举和模式匹配](#7-枚举和模式匹配)
- [8. 包、Crates 与模块](#8-包crates-与模块)
- [9. 常见集合](#9-常见集合)
- [10. 错误处理](#10-错误处理)
- [11. 泛型、Trait 和生命周期](#11-泛型trait-和生命周期)
- [12. 编写自动化测试](#12-编写自动化测试)
- [13. 一个 I/O 项目：构建命令行程序](#13-一个-io-项目构建命令行程序)
- [14. 函数式语言特性：迭代器与闭包](#14-函数式语言特性迭代器与闭包)
- [15. 更多关于 Cargo 和 Crates.io 的内容](#15-更多关于-cargo-和-cratesio-的内容)
- [16. 智能指针](#16-智能指针)
- [17. 无畏并发](#17-无畏并发)
- [18. 异步编程基础：Async、Await、Future 与 Stream](#18-异步编程基础asyncawaitfuture-与-stream)
- [19. 面向对象编程特性](#19-面向对象编程特性)
- [20. 模式与模式匹配](#20-模式与模式匹配)
- [21. 高级特性](#21-高级特性)
- [22. 最后的项目：构建多线程 web server](#22-最后的项目构建多线程-web-server)
- [23. 附录](#23-附录)
- [24. new](#24-new)

<!-- endregion:toc -->

## 1. TNotes.rust

- [ ] [0001. TNotes.rust](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0001.%20TNotes.rust/README.md)

## 2. 入门指南

- [ ] [0002. 入门指南](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0002.%20%E5%85%A5%E9%97%A8%E6%8C%87%E5%8D%97/README.md)
- [ ] [0003. 安装](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0003.%20%E5%AE%89%E8%A3%85/README.md)
- [ ] [0004. Hello, World!](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0004.%20Hello%2C%20World!/README.md)
- [ ] [0005. Hello, Cargo!](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0005.%20Hello%2C%20Cargo!/README.md)

## 3. 编写一个猜数字游戏

- [ ] [0006. 编写一个猜数字游戏](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0006.%20%E7%BC%96%E5%86%99%E4%B8%80%E4%B8%AA%E7%8C%9C%E6%95%B0%E5%AD%97%E6%B8%B8%E6%88%8F/README.md)

## 4. 常见编程概念

- [ ] [0007. 常见编程概念](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0007.%20%E5%B8%B8%E8%A7%81%E7%BC%96%E7%A8%8B%E6%A6%82%E5%BF%B5/README.md)
- [ ] [0008. 变量与可变性](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0008.%20%E5%8F%98%E9%87%8F%E4%B8%8E%E5%8F%AF%E5%8F%98%E6%80%A7/README.md)
- [ ] [0009. 数据类型](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0009.%20%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B/README.md)
- [ ] [0010. 函数](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0010.%20%E5%87%BD%E6%95%B0/README.md)
- [ ] [0011. 注释](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0011.%20%E6%B3%A8%E9%87%8A/README.md)
- [ ] [0012. 控制流](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0012.%20%E6%8E%A7%E5%88%B6%E6%B5%81/README.md)

## 5. 认识所有权

- [ ] [0013. 认识所有权](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0013.%20%E8%AE%A4%E8%AF%86%E6%89%80%E6%9C%89%E6%9D%83/README.md)
- [ ] [0014. 什么是所有权？](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0014.%20%E4%BB%80%E4%B9%88%E6%98%AF%E6%89%80%E6%9C%89%E6%9D%83%EF%BC%9F/README.md)
- [ ] [0015. 引用与借用](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0015.%20%E5%BC%95%E7%94%A8%E4%B8%8E%E5%80%9F%E7%94%A8/README.md)
- [ ] [0016. Slice 类型](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0016.%20Slice%20%E7%B1%BB%E5%9E%8B/README.md)

## 6. 使用结构体组织相关联的数据

- [ ] [0017. 使用结构体组织相关联的数据](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0017.%20%E4%BD%BF%E7%94%A8%E7%BB%93%E6%9E%84%E4%BD%93%E7%BB%84%E7%BB%87%E7%9B%B8%E5%85%B3%E8%81%94%E7%9A%84%E6%95%B0%E6%8D%AE/README.md)
- [ ] [0018. 结构体的定义和实例化](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0018.%20%E7%BB%93%E6%9E%84%E4%BD%93%E7%9A%84%E5%AE%9A%E4%B9%89%E5%92%8C%E5%AE%9E%E4%BE%8B%E5%8C%96/README.md)
- [ ] [0019. 结构体示例程序](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0019.%20%E7%BB%93%E6%9E%84%E4%BD%93%E7%A4%BA%E4%BE%8B%E7%A8%8B%E5%BA%8F/README.md)
- [ ] [0020. 方法语法](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0020.%20%E6%96%B9%E6%B3%95%E8%AF%AD%E6%B3%95/README.md)

## 7. 枚举和模式匹配

- [ ] [0021. 枚举和模式匹配](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0021.%20%E6%9E%9A%E4%B8%BE%E5%92%8C%E6%A8%A1%E5%BC%8F%E5%8C%B9%E9%85%8D/README.md)
- [ ] [0022. 枚举的定义](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0022.%20%E6%9E%9A%E4%B8%BE%E7%9A%84%E5%AE%9A%E4%B9%89/README.md)
- [ ] [0023. match 控制流结构](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0023.%20match%20%E6%8E%A7%E5%88%B6%E6%B5%81%E7%BB%93%E6%9E%84/README.md)
- [ ] [0024. if let 和 let else 简洁控制流](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0024.%20if%20let%20%E5%92%8C%20let%20else%20%E7%AE%80%E6%B4%81%E6%8E%A7%E5%88%B6%E6%B5%81/README.md)

## 8. 包、Crates 与模块

- [ ] [0025. 包、Crates 与模块](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0025.%20%E5%8C%85%E3%80%81Crates%20%E4%B8%8E%E6%A8%A1%E5%9D%97/README.md)
- [ ] [0026. 包和 Crate](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0026.%20%E5%8C%85%E5%92%8C%20Crate/README.md)
- [ ] [0027. 定义模块来控制作用域与私有性](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0027.%20%E5%AE%9A%E4%B9%89%E6%A8%A1%E5%9D%97%E6%9D%A5%E6%8E%A7%E5%88%B6%E4%BD%9C%E7%94%A8%E5%9F%9F%E4%B8%8E%E7%A7%81%E6%9C%89%E6%80%A7/README.md)
- [ ] [0028. 引用模块树中项的路径](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0028.%20%E5%BC%95%E7%94%A8%E6%A8%A1%E5%9D%97%E6%A0%91%E4%B8%AD%E9%A1%B9%E7%9A%84%E8%B7%AF%E5%BE%84/README.md)
- [ ] [0029. 使用 use 关键字将路径引入作用域](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0029.%20%E4%BD%BF%E7%94%A8%20use%20%E5%85%B3%E9%94%AE%E5%AD%97%E5%B0%86%E8%B7%AF%E5%BE%84%E5%BC%95%E5%85%A5%E4%BD%9C%E7%94%A8%E5%9F%9F/README.md)
- [ ] [0030. 将模块拆分成多个文件](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0030.%20%E5%B0%86%E6%A8%A1%E5%9D%97%E6%8B%86%E5%88%86%E6%88%90%E5%A4%9A%E4%B8%AA%E6%96%87%E4%BB%B6/README.md)

## 9. 常见集合

- [ ] [0031. 常见集合](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0031.%20%E5%B8%B8%E8%A7%81%E9%9B%86%E5%90%88/README.md)
- [ ] [0032. 使用 Vector 储存列表](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0032.%20%E4%BD%BF%E7%94%A8%20Vector%20%E5%82%A8%E5%AD%98%E5%88%97%E8%A1%A8/README.md)
- [ ] [0033. 使用字符串储存 UTF-8 编码的文本](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0033.%20%E4%BD%BF%E7%94%A8%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%82%A8%E5%AD%98%20UTF-8%20%E7%BC%96%E7%A0%81%E7%9A%84%E6%96%87%E6%9C%AC/README.md)
- [ ] [0034. 使用 Hash Map 储存键值对](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0034.%20%E4%BD%BF%E7%94%A8%20Hash%20Map%20%E5%82%A8%E5%AD%98%E9%94%AE%E5%80%BC%E5%AF%B9/README.md)

## 10. 错误处理

- [ ] [0035. 错误处理](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0035.%20%E9%94%99%E8%AF%AF%E5%A4%84%E7%90%86/README.md)
- [ ] [0036. 用 panic! 处理不可恢复的错误](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0036.%20%E7%94%A8%20panic!%20%E5%A4%84%E7%90%86%E4%B8%8D%E5%8F%AF%E6%81%A2%E5%A4%8D%E7%9A%84%E9%94%99%E8%AF%AF/README.md)
- [ ] [0037. 用 Result 处理可恢复的错误](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0037.%20%E7%94%A8%20Result%20%E5%A4%84%E7%90%86%E5%8F%AF%E6%81%A2%E5%A4%8D%E7%9A%84%E9%94%99%E8%AF%AF/README.md)
- [ ] [0038. 要不要 panic!](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0038.%20%E8%A6%81%E4%B8%8D%E8%A6%81%20panic!/README.md)

## 11. 泛型、Trait 和生命周期

- [ ] [0039. 泛型、Trait 和生命周期](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0039.%20%E6%B3%9B%E5%9E%8B%E3%80%81Trait%20%E5%92%8C%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F/README.md)
- [ ] [0040. 泛型数据类型](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0040.%20%E6%B3%9B%E5%9E%8B%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B/README.md)
- [ ] [0041. Trait：定义共同行为](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0041.%20Trait%EF%BC%9A%E5%AE%9A%E4%B9%89%E5%85%B1%E5%90%8C%E8%A1%8C%E4%B8%BA/README.md)
- [ ] [0042. 生命周期确保引用有效](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0042.%20%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F%E7%A1%AE%E4%BF%9D%E5%BC%95%E7%94%A8%E6%9C%89%E6%95%88/README.md)

## 12. 编写自动化测试

- [ ] [0043. 编写自动化测试](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0043.%20%E7%BC%96%E5%86%99%E8%87%AA%E5%8A%A8%E5%8C%96%E6%B5%8B%E8%AF%95/README.md)
- [ ] [0044. 如何编写测试](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0044.%20%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%E6%B5%8B%E8%AF%95/README.md)
- [ ] [0045. 控制测试如何运行](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0045.%20%E6%8E%A7%E5%88%B6%E6%B5%8B%E8%AF%95%E5%A6%82%E4%BD%95%E8%BF%90%E8%A1%8C/README.md)
- [ ] [0046. 测试的组织结构](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0046.%20%E6%B5%8B%E8%AF%95%E7%9A%84%E7%BB%84%E7%BB%87%E7%BB%93%E6%9E%84/README.md)

## 13. 一个 I/O 项目：构建命令行程序

- [ ] [0047. 一个 IO 项目：构建命令行程序](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0047.%20%E4%B8%80%E4%B8%AA%20IO%20%E9%A1%B9%E7%9B%AE%EF%BC%9A%E6%9E%84%E5%BB%BA%E5%91%BD%E4%BB%A4%E8%A1%8C%E7%A8%8B%E5%BA%8F/README.md)
- [ ] [0048. 接受命令行参数](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0048.%20%E6%8E%A5%E5%8F%97%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%8F%82%E6%95%B0/README.md)
- [ ] [0049. 读取文件](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0049.%20%E8%AF%BB%E5%8F%96%E6%96%87%E4%BB%B6/README.md)
- [ ] [0050. 重构以改进模块化与错误处理](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0050.%20%E9%87%8D%E6%9E%84%E4%BB%A5%E6%94%B9%E8%BF%9B%E6%A8%A1%E5%9D%97%E5%8C%96%E4%B8%8E%E9%94%99%E8%AF%AF%E5%A4%84%E7%90%86/README.md)
- [ ] [0051. 采用测试驱动开发完善库的功能](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0051.%20%E9%87%87%E7%94%A8%E6%B5%8B%E8%AF%95%E9%A9%B1%E5%8A%A8%E5%BC%80%E5%8F%91%E5%AE%8C%E5%96%84%E5%BA%93%E7%9A%84%E5%8A%9F%E8%83%BD/README.md)
- [ ] [0052. 处理环境变量](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0052.%20%E5%A4%84%E7%90%86%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F/README.md)
- [ ] [0053. 将错误信息输出到标准错误而不是标准输出](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0053.%20%E5%B0%86%E9%94%99%E8%AF%AF%E4%BF%A1%E6%81%AF%E8%BE%93%E5%87%BA%E5%88%B0%E6%A0%87%E5%87%86%E9%94%99%E8%AF%AF%E8%80%8C%E4%B8%8D%E6%98%AF%E6%A0%87%E5%87%86%E8%BE%93%E5%87%BA/README.md)

## 14. 函数式语言特性：迭代器与闭包

- [ ] [0054. 函数式语言特性：迭代器与闭包](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0054.%20%E5%87%BD%E6%95%B0%E5%BC%8F%E8%AF%AD%E8%A8%80%E7%89%B9%E6%80%A7%EF%BC%9A%E8%BF%AD%E4%BB%A3%E5%99%A8%E4%B8%8E%E9%97%AD%E5%8C%85/README.md)
- [ ] [0055. 闭包：可以捕获其环境的匿名函数](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0055.%20%E9%97%AD%E5%8C%85%EF%BC%9A%E5%8F%AF%E4%BB%A5%E6%8D%95%E8%8E%B7%E5%85%B6%E7%8E%AF%E5%A2%83%E7%9A%84%E5%8C%BF%E5%90%8D%E5%87%BD%E6%95%B0/README.md)
- [ ] [0056. 使用迭代器处理元素序列](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0056.%20%E4%BD%BF%E7%94%A8%E8%BF%AD%E4%BB%A3%E5%99%A8%E5%A4%84%E7%90%86%E5%85%83%E7%B4%A0%E5%BA%8F%E5%88%97/README.md)
- [ ] [0057. 改进之前的 IO 项目](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0057.%20%E6%94%B9%E8%BF%9B%E4%B9%8B%E5%89%8D%E7%9A%84%20IO%20%E9%A1%B9%E7%9B%AE/README.md)
- [ ] [0058. 性能比较：循环对迭代器](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0058.%20%E6%80%A7%E8%83%BD%E6%AF%94%E8%BE%83%EF%BC%9A%E5%BE%AA%E7%8E%AF%E5%AF%B9%E8%BF%AD%E4%BB%A3%E5%99%A8/README.md)

## 15. 更多关于 Cargo 和 Crates.io 的内容

- [ ] [0059. 更多关于 Cargo 和 Crates.io 的内容](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0059.%20%E6%9B%B4%E5%A4%9A%E5%85%B3%E4%BA%8E%20Cargo%20%E5%92%8C%20Crates.io%20%E7%9A%84%E5%86%85%E5%AE%B9/README.md)
- [ ] [0060. 采用发布配置自定义构建](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0060.%20%E9%87%87%E7%94%A8%E5%8F%91%E5%B8%83%E9%85%8D%E7%BD%AE%E8%87%AA%E5%AE%9A%E4%B9%89%E6%9E%84%E5%BB%BA/README.md)
- [ ] [0061. 将 crate 发布到 Crates.io](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0061.%20%E5%B0%86%20crate%20%E5%8F%91%E5%B8%83%E5%88%B0%20Crates.io/README.md)
- [ ] [0062. Cargo 工作空间](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0062.%20Cargo%20%E5%B7%A5%E4%BD%9C%E7%A9%BA%E9%97%B4/README.md)
- [ ] [0063. 使用 cargo install 安装二进制文件](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0063.%20%E4%BD%BF%E7%94%A8%20cargo%20install%20%E5%AE%89%E8%A3%85%E4%BA%8C%E8%BF%9B%E5%88%B6%E6%96%87%E4%BB%B6/README.md)
- [ ] [0064. Cargo 自定义扩展命令](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0064.%20Cargo%20%E8%87%AA%E5%AE%9A%E4%B9%89%E6%89%A9%E5%B1%95%E5%91%BD%E4%BB%A4/README.md)

## 16. 智能指针

- [ ] [0065. 智能指针](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0065.%20%E6%99%BA%E8%83%BD%E6%8C%87%E9%92%88/README.md)
- [ ] [0066. 使用 Box(T) 指向堆上数据](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0066.%20%E4%BD%BF%E7%94%A8%20Box(T)%20%E6%8C%87%E5%90%91%E5%A0%86%E4%B8%8A%E6%95%B0%E6%8D%AE/README.md)
- [ ] [0067. 使用 Deref Trait 将智能指针当作常规引用处理](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0067.%20%E4%BD%BF%E7%94%A8%20Deref%20Trait%20%E5%B0%86%E6%99%BA%E8%83%BD%E6%8C%87%E9%92%88%E5%BD%93%E4%BD%9C%E5%B8%B8%E8%A7%84%E5%BC%95%E7%94%A8%E5%A4%84%E7%90%86/README.md)
- [ ] [0068. 使用 Drop Trait 运行清理代码](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0068.%20%E4%BD%BF%E7%94%A8%20Drop%20Trait%20%E8%BF%90%E8%A1%8C%E6%B8%85%E7%90%86%E4%BB%A3%E7%A0%81/README.md)
- [ ] [0069. Rc(T) 引用计数智能指针](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0069.%20Rc(T)%20%E5%BC%95%E7%94%A8%E8%AE%A1%E6%95%B0%E6%99%BA%E8%83%BD%E6%8C%87%E9%92%88/README.md)
- [ ] [0070. RefCell(T) 与内部可变性模式](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0070.%20RefCell(T)%20%E4%B8%8E%E5%86%85%E9%83%A8%E5%8F%AF%E5%8F%98%E6%80%A7%E6%A8%A1%E5%BC%8F/README.md)
- [ ] [0071. 引用循环会导致内存泄漏](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0071.%20%E5%BC%95%E7%94%A8%E5%BE%AA%E7%8E%AF%E4%BC%9A%E5%AF%BC%E8%87%B4%E5%86%85%E5%AD%98%E6%B3%84%E6%BC%8F/README.md)

## 17. 无畏并发

- [ ] [0072. 无畏并发](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0072.%20%E6%97%A0%E7%95%8F%E5%B9%B6%E5%8F%91/README.md)
- [ ] [0073. 使用线程同时地运行代码](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0073.%20%E4%BD%BF%E7%94%A8%E7%BA%BF%E7%A8%8B%E5%90%8C%E6%97%B6%E5%9C%B0%E8%BF%90%E8%A1%8C%E4%BB%A3%E7%A0%81/README.md)
- [ ] [0074. 使用消息传递在线程间通信](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0074.%20%E4%BD%BF%E7%94%A8%E6%B6%88%E6%81%AF%E4%BC%A0%E9%80%92%E5%9C%A8%E7%BA%BF%E7%A8%8B%E9%97%B4%E9%80%9A%E4%BF%A1/README.md)
- [ ] [0075. 共享状态并发](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0075.%20%E5%85%B1%E4%BA%AB%E7%8A%B6%E6%80%81%E5%B9%B6%E5%8F%91/README.md)
- [ ] [0076. 使用 Sync 与 Send Traits 的可扩展并发](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0076.%20%E4%BD%BF%E7%94%A8%20Sync%20%E4%B8%8E%20Send%20Traits%20%E7%9A%84%E5%8F%AF%E6%89%A9%E5%B1%95%E5%B9%B6%E5%8F%91/README.md)

## 18. 异步编程基础：Async、Await、Future 与 Stream

- [ ] [0077. 异步编程基础：Async、Await、Future 与 Stream](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0077.%20%E5%BC%82%E6%AD%A5%E7%BC%96%E7%A8%8B%E5%9F%BA%E7%A1%80%EF%BC%9AAsync%E3%80%81Await%E3%80%81Future%20%E4%B8%8E%20Stream/README.md)
- [ ] [0078. Futures 和 async 语法](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0078.%20Futures%20%E5%92%8C%20async%20%E8%AF%AD%E6%B3%95/README.md)
- [ ] [0079. 并发与 async](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0079.%20%E5%B9%B6%E5%8F%91%E4%B8%8E%20async/README.md)
- [ ] [0080. 使用任意数量的 futures](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0080.%20%E4%BD%BF%E7%94%A8%E4%BB%BB%E6%84%8F%E6%95%B0%E9%87%8F%E7%9A%84%20futures/README.md)
- [ ] [0081. Stream：按顺序出现的 Future](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0081.%20Stream%EF%BC%9A%E6%8C%89%E9%A1%BA%E5%BA%8F%E5%87%BA%E7%8E%B0%E7%9A%84%20Future/README.md)
- [ ] [0082. 深入理解 async 相关的 traits](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0082.%20%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3%20async%20%E7%9B%B8%E5%85%B3%E7%9A%84%20traits/README.md)
- [ ] [0083. future、任务和线程](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0083.%20future%E3%80%81%E4%BB%BB%E5%8A%A1%E5%92%8C%E7%BA%BF%E7%A8%8B/README.md)

## 19. 面向对象编程特性

- [ ] [0084. 面向对象编程特性](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0084.%20%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%BC%96%E7%A8%8B%E7%89%B9%E6%80%A7/README.md)
- [ ] [0085. 面向对象语言的特征](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0085.%20%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E8%AF%AD%E8%A8%80%E7%9A%84%E7%89%B9%E5%BE%81/README.md)
- [ ] [0086. 使用 trait object 来抽象出共享行为](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0086.%20%E4%BD%BF%E7%94%A8%20trait%20object%20%E6%9D%A5%E6%8A%BD%E8%B1%A1%E5%87%BA%E5%85%B1%E4%BA%AB%E8%A1%8C%E4%B8%BA/README.md)
- [ ] [0087. 面向对象设计模式的实现](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0087.%20%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F%E7%9A%84%E5%AE%9E%E7%8E%B0/README.md)

## 20. 模式与模式匹配

- [ ] [0088. 模式与模式匹配](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0088.%20%E6%A8%A1%E5%BC%8F%E4%B8%8E%E6%A8%A1%E5%BC%8F%E5%8C%B9%E9%85%8D/README.md)
- [ ] [0089. 所有可能会用到模式的位置](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0089.%20%E6%89%80%E6%9C%89%E5%8F%AF%E8%83%BD%E4%BC%9A%E7%94%A8%E5%88%B0%E6%A8%A1%E5%BC%8F%E7%9A%84%E4%BD%8D%E7%BD%AE/README.md)
- [ ] [0090. Refutability（可反驳性）：模式是否会匹配失效](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0090.%20Refutability%EF%BC%88%E5%8F%AF%E5%8F%8D%E9%A9%B3%E6%80%A7%EF%BC%89%EF%BC%9A%E6%A8%A1%E5%BC%8F%E6%98%AF%E5%90%A6%E4%BC%9A%E5%8C%B9%E9%85%8D%E5%A4%B1%E6%95%88/README.md)
- [ ] [0091. 模式语法](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0091.%20%E6%A8%A1%E5%BC%8F%E8%AF%AD%E6%B3%95/README.md)

## 21. 高级特性

- [ ] [0092. 高级特性](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0092.%20%E9%AB%98%E7%BA%A7%E7%89%B9%E6%80%A7/README.md)
- [ ] [0093. 不安全 Rust](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0093.%20%E4%B8%8D%E5%AE%89%E5%85%A8%20Rust/README.md)
- [ ] [0094. 高级 trait](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0094.%20%E9%AB%98%E7%BA%A7%20trait/README.md)
- [ ] [0095. 高级类型](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0095.%20%E9%AB%98%E7%BA%A7%E7%B1%BB%E5%9E%8B/README.md)
- [ ] [0096. 高级函数与闭包](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0096.%20%E9%AB%98%E7%BA%A7%E5%87%BD%E6%95%B0%E4%B8%8E%E9%97%AD%E5%8C%85/README.md)
- [ ] [0097. 宏](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0097.%20%E5%AE%8F/README.md)

## 22. 最后的项目：构建多线程 web server

- [ ] [0098. 最后的项目：构建多线程 web server](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0098.%20%E6%9C%80%E5%90%8E%E7%9A%84%E9%A1%B9%E7%9B%AE%EF%BC%9A%E6%9E%84%E5%BB%BA%E5%A4%9A%E7%BA%BF%E7%A8%8B%20web%20server/README.md)
- [ ] [0099. 构建单线程 web server](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0099.%20%E6%9E%84%E5%BB%BA%E5%8D%95%E7%BA%BF%E7%A8%8B%20web%20server/README.md)
- [ ] [0100. 将单线程 server 变为多线程 server](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0100.%20%E5%B0%86%E5%8D%95%E7%BA%BF%E7%A8%8B%20server%20%E5%8F%98%E4%B8%BA%E5%A4%9A%E7%BA%BF%E7%A8%8B%20server/README.md)
- [ ] [0101. 优雅停机与清理](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0101.%20%E4%BC%98%E9%9B%85%E5%81%9C%E6%9C%BA%E4%B8%8E%E6%B8%85%E7%90%86/README.md)

## 23. 附录

- [ ] [0102. 附录](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0102.%20%E9%99%84%E5%BD%95/README.md)
- [ ] [0103. A - 关键字](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0103.%20A%20-%20%E5%85%B3%E9%94%AE%E5%AD%97/README.md)
- [ ] [0104. B - 运算符与符号](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0104.%20B%20-%20%E8%BF%90%E7%AE%97%E7%AC%A6%E4%B8%8E%E7%AC%A6%E5%8F%B7/README.md)
- [ ] [0105. C - 可派生的 trait](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0105.%20C%20-%20%E5%8F%AF%E6%B4%BE%E7%94%9F%E7%9A%84%20trait/README.md)
- [ ] [0106. D - 实用开发工具](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0106.%20D%20-%20%E5%AE%9E%E7%94%A8%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7/README.md)
- [ ] [0107. E - 版本](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0107.%20E%20-%20%E7%89%88%E6%9C%AC/README.md)
- [ ] [0108. F - 本书译本](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0108.%20F%20-%20%E6%9C%AC%E4%B9%A6%E8%AF%91%E6%9C%AC/README.md)
- [ ] [0109. G - Rust 是如何开发的与 「Nightly Rust」](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0109.%20G%20-%20Rust%20%E6%98%AF%E5%A6%82%E4%BD%95%E5%BC%80%E5%8F%91%E7%9A%84%E4%B8%8E%20%E3%80%8CNightly%20Rust%E3%80%8D/README.md)

## 24. new

- [ ] [0110. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0110.%20new/README.md)
- [ ] [0111. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0111.%20new/README.md)
- [ ] [0112. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0112.%20new/README.md)
- [ ] [0113. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0113.%20new/README.md)
- [ ] [0114. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0114.%20new/README.md)
- [ ] [0115. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0115.%20new/README.md)
- [ ] [0116. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0116.%20new/README.md)
- [ ] [0117. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0117.%20new/README.md)
- [ ] [0118. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0118.%20new/README.md)
- [ ] [0119. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0119.%20new/README.md)
- [ ] [0120. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0120.%20new/README.md)
- [ ] [0121. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0121.%20new/README.md)
- [ ] [0122. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0122.%20new/README.md)
- [ ] [0123. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0123.%20new/README.md)
- [ ] [0124. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0124.%20new/README.md)
- [ ] [0125. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0125.%20new/README.md)
- [ ] [0126. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0126.%20new/README.md)
- [ ] [0127. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0127.%20new/README.md)
- [ ] [0128. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0128.%20new/README.md)
- [ ] [0129. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0129.%20new/README.md)
- [ ] [0130. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0130.%20new/README.md)
- [ ] [0131. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0131.%20new/README.md)
- [ ] [0132. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0132.%20new/README.md)
- [ ] [0133. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0133.%20new/README.md)
- [ ] [0134. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0134.%20new/README.md)
- [ ] [0135. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0135.%20new/README.md)
- [ ] [0136. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0136.%20new/README.md)
- [ ] [0137. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0137.%20new/README.md)
- [ ] [0138. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0138.%20new/README.md)
- [ ] [0139. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0139.%20new/README.md)
- [ ] [0140. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0140.%20new/README.md)
- [ ] [0141. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0141.%20new/README.md)
- [ ] [0142. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0142.%20new/README.md)
- [ ] [0143. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0143.%20new/README.md)
- [ ] [0144. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0144.%20new/README.md)
- [ ] [0145. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0145.%20new/README.md)
- [ ] [0146. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0146.%20new/README.md)
- [ ] [0147. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0147.%20new/README.md)
- [ ] [0148. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0148.%20new/README.md)
- [ ] [0149. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0149.%20new/README.md)
- [ ] [0150. new](https://github.com/tnotesjs/TNotes.rust/tree/main/notes/0150.%20new/README.md)
