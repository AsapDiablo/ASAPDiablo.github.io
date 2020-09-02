---
title: Golang
date: 2020-07-22 15:04:25
tags: [go,defer,goruntine, go runtime, gc]
categories: tech
keywords: go
---

# Golang
## go 程序启动
### 协程启动过程
- 与Linux C程序启动过程的区别
## go runtime
### 调度器
- 调度G-P-M模型
### 内存管理
### 垃圾回收
- GC并发标记清除
- 三色标记法
### 反射
### 问题
#### go runtime和java 虚拟机, python虚拟机有很什么区别
- 操作系统线程和java线程:https://www.jianshu.com/p/7c980955627e
#### go main函数会对应一个goroutine吗？
## go 并发
### select关键字
### 协程概念
### 协程调度原理

## 变量类型

### 变量内存分配
- 编译器逃逸分析
- 引用类型new和make的区别
  - new为指定类型分配零值内存并返回指针，不会构造类型内部结构和初始化方式，因此会对内置类型例如map采用new并不会分配键值结构。
### const关键字


## 指针
**访问指针之前一定要判空防止空指针导致panic**

## 编程技巧
### 面向对象编程
