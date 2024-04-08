---
title: "TechStack背后的故事: 高频性能优化"
description: oepr
published: 2023-08-18T23:07:33+08:00
category: 技术
draft: false
tags: [] 
---

这里我挺推荐一本关于 Go 的小书 [Go 语言高性能编程](https://geektutu.com/post/high-performance-go.html)

我之前不重视性能优化

先说一下整体的思路，就像模仿那个笔记本维修厮修电脑有三版斧一般，这几天我整体思路也基本就是三板斧: Benchmark、Pprof、减少CG。🤔三板斧干下去，能解决就解决，解决不了就摇人了。🤣

## 一些常见的优化项
### String拼接 + 和 builder
相信大家都知道在

### 去重
通过 Map 去重

### Json
使用 Easyjson 而不是原生的 Json


### 后续
