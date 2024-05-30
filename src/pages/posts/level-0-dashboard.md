---
layout: '../../layouts/MarkdownPost.astro'
title: '仪表盘'
pubDate: 2024-05-28
description: '仪表盘使用文档'
author: 'howe'
cover:
    url: '/public/images/title1.png'
    square: '/public/images/title1.png'
    alt: 'cover'
tags: ["监控中心"] 
theme: 'dark'
featured: false

meta:
 - name: author
   content: 作者是我
 - name: keywords
   content: key3, key4
keywords: key1, key2, key3, key4

---

# 功能
利用数据可视化的方式，将高度复杂的数据转化为有助于解决用户业务问题的关键要素。能查看到客观有效的信息。

# 系统设置
### 1、导入仪表盘
Import dashboard

Import dashboard from file or Grafana.com

可以从官网模板


### 2、数据源
#### 2.1基本概念
支持许多不同的数据源。每个数据源都有一个特定的查询编辑器,该编辑器定制的特性和功能是公开的特定数据来源。 官方支持以下数据源:Graphite，Elasticsearch，InfluxDB，Prometheus，Cloudwatch，MySQL和OpenTSDB等。

每个数据源的查询语言和能力都是不同的。你可以把来自多个数据源的数据组合到一个仪表板，但每一个面板被绑定到一个特定的数据源,它就属于一个特定的组织。

![|inline](/public/images/1.png)

可通过添加数据源增加不同种类的数据源给与Dashboards使用

![|inline](/public/images/2.png)

# Dashboards
### 功能介绍
通过获取对应的仪表盘列表数据生成对应的仪表盘菜单

# HOME
默认仪表盘


# 操作演示
![|inline](/public/images/1.gif)