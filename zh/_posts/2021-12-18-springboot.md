---
layout: post
title: 'SpringBoot'
date: 2021-12-18
author: 李乐升
cover: 'https://images.unsplash.com/photo-1651010967601-8cc281c00dc6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=764&q=80'
tags: Java
language: zh
---
# 注解讲解

## @Configuration

标注在类上，表明该类是一个配置类，在类中可以使用@Bean注解为容器中添加组件；配置类本身也是组件；proxyBeanMethods属性用来指定是否要代理bean的方法

![image-20210209223802665](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210209223802665.png)