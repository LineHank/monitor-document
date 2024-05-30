---
layout: '../../layouts/MarkdownPost.astro'
title: '数据采集'
pubDate: 2024-05-28
description: '数据采集使用文档'
author: 'howe'
cover:
    url: '/public/images/title9.jpg'
    square: '/public/images/title9.jpg'
    alt: 'cover'
tags: ["监控中心"] 
theme: 'dark'
featured: false
---

# 功能
自动化安装各类exporter

# 使用说明
1、vm-agent 单实例，只有一种安装类型，只需要复制到对应服务器进行安装和卸载即可

![|inline](/public/images/19.png)

![|inline](/public/images/20.png)

2、node-exporter 单实例，只有一种安装类型，用于服务器监控指标信息的拉取

![|inline](/public/images/21.png)

![|inline](/public/images/22.png)

2、mysqld-exporter 多实例，需要根据不同的参数设置多种实例，譬如不同数据库的ip、账号密码

![|inline](/public/images/23.png)

![|inline](/public/images/24.png)



