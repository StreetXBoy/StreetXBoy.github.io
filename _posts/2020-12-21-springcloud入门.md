---
layout:     post                    # 使用的布局（不需要改）
title:      springcloud入门    # 标题 
subtitle:   springcloud入门  #副标题
date:       2020-12-21              # 时间
author:     陈祥瑞                  # 作者
catalog: true                       # 是否归档
tags:                               #标签
    - Java
---
# springcloud与微服务
## 微服务的本质
到底什么是微服务？？？  -------    本质上就是统一的功能切成各种模块，然后每个模块独自开发通过restful风格api进行开发，然后通过注册中心进行管理！！！！！！

## springcloud的本质
到底springcloud是什么意思与springboot的关系？？？？   ------------- 本质上springcloud是基于springboot之上开发的一个微服务框架！！！！！

## springcloud常用组件

+ 服务的注册与发现
Eurake、Consul、Zookeeper、nacos

+ 负载均衡
fegin 远程调用
ribbon 负载均衡组件
fegin+ribbon实现

+ 容错
Hystrix

+ 路由
Zuul、springcloud gateway

+ 分布式消息传递
redis、rabbitmq、kafka

+ 版本化配置
springcloud config + spring cloud bus 总线



