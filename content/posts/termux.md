---
title: "我的第一篇 Termux 博客"
date: "2026-10-13T14:58:00Z"
lastmod: "2026-10-13T14:58:00Z"
draft: false
tags: ["hugo", "termux", "教程"]
categories: []
---

用 Termux 在手机上写博客：hugo 构建、本地预览、git 推送一条龙。

Termux 里的 hugo 是 **extended** 版本，支持 SCSS 主题。配合 EdgeOne Pages，
push 之后自动发布，全程不需要电脑。

## 常用命令

- `newpost "标题"` 新建文章
- `autotag` 智能补标签
- `preview` 本地预览
- `deploy "信息"` 构建并发布
