---
layout: '../../layouts/MarkdownPost.astro'
title: '数据源'
pubDate: 2024-05-28
description: '数据源使用文档'
author: 'howe'
cover:
    url: '/monitor-document/images/title8.jpg'
    square: '/monitor-document/images/title8.jpg'
    alt: 'cover'
tags: ["监控中心"] 
theme: 'dark'
featured: false
---

# 功能
1、新增数据源，用于通过数据源获取对应的数据信息和告警信息

![|inline](/monitor-document/images/18.png)

常见时序数据库配置示例（兼容 Prometheus 查询 API）：
1. Prometheus: http://localhost:9090/
2. Thanos: http://localhost:19192/
3. VictoriaMetrics: http://{vmselect}:8481/select/0/prometheus/
4. M3: http://localhost:7201/
5. SLS: https://{project}.{sls-enpoint}/prometheus/{project}/{metricstore}/


