---
title: go note
date: 2020-07-22 15:04:25
tags: go defer
categories: tech
keywords: go
---

## Golang
### 为什么称go是静态语言
- 首先静态语言和动态语言的定义
  - 静态语言:代码在编译期提供约束:什么约束、约束如何实现
  - 动态语言:代码在运行期提供约束
### 为什么Golang采用静态编译
### const关键字
### 变量类型
- 引用类型new和make的区别
  - new为指定类型分配零值内存并返回指针，不会构造类型内部结构和初始化方式，因此会对内置类型例如map采用new并不会分配键值结构。
