# Yulian's Blog

这是我的个人博客，记录生活、阅读、科学、技术和故事。

访问地址：

https://yulianxia.github.io

## 内容结构

- `生活记录`：生活经历、家庭、城市和日常观察
- `日有所思`：阅读、复盘和阶段性思考
- `科学和技术`：科学笔记、技术记录和学习过程
- `故事`：虚构写作和短篇故事

## 如何更新文章

文章保存在 `_posts` 文件夹里。

新增文章时，把 Markdown 文件放进对应分类文件夹：

- `_posts/life/`
- `_posts/reading/`
- `_posts/science/`
- `_posts/tech/`
- `_posts/story/`

文件名格式：

```text
YYYY-MM-DD-title.md
```

文章开头需要保留这样的信息：

```yaml
---
layout: post
title: "文章标题"
date: 2026-06-02 10:00:00 +0100
description: 简短说明
tags: [标签1, 标签2]
---
```

## 页面

- 首页：`index.html`
- 分类页：`categories.html`
- 标签页：`tags.html`
- 文章模板：`_layouts/post.html`
- 主样式：`assets/css/main.css`
