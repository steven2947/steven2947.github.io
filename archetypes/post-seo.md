---
title: "文章标题"
date: {{ .Date }}
draft: false

# SEO 优化
description: "文章描述，用于搜索引擎显示，建议 150-160 字符"
keywords: ["关键词1", "关键词2", "关键词3"]
author: "Steven"

# 分类和标签
categories: ["技术分类"]
tags: ["标签1", "标签2", "标签3"]

# 特色图片（用于社交媒体分享）
image: "/img/posts/featured-image.jpg"

# 文章摘要
summary: "文章摘要，用于列表页显示"

# 是否显示目录
toc: true

# 是否显示阅读时间
ShowReadingTime: true

# 是否显示分享按钮
ShowShareButtons: true

# 是否显示导航链接
ShowPostNavLinks: true

# 是否显示代码复制按钮
ShowCodeCopyButtons: true

# 是否允许评论
comments: true

# 结构化数据
[params.structuredData]
  type = "Article"
  author = "Steven"
  publisher = "Steven's Blog"
---

<!-- 文章内容从这里开始 -->

## 引言

在这里写文章的引言部分...

## 主要内容

### 子标题1

内容内容...

### 子标题2

内容内容...

## 总结

在这里写文章的总结部分...

---

**相关文章：**
- [相关文章1](/posts/related-post-1/)
- [相关文章2](/posts/related-post-2/)

**标签：** {{< tags >}}
