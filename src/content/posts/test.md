---
title: 这是一个测试
published: 2026-07-13 # 发布日期，格式YYYY-MM-DD，决定文章排序
updated: 2026-07-13 # 可选，更新日期，会显示在文章页
description: 这是一个描述
tags: [滚木] # 可选，多个标签用逗号分隔
category: 技术 # 必填，一个大分类，比如「技术」「生活」「随笔」
draft: false # 必填！false=线上发布，true=仅本地可见（写一半的文章设true）
image: /assets/images/2025-12-19.jpg # 可选，文章封面图，放public/assets/images下
---

# 一级标题（文章标题 already 有，正文少用）
## 二级标题（正文主标题）
### 三级标题（小节标题）

段落之间空一行。

**加粗** _斜体_ `行内代码`

- 无序列表项1
- 无序列表项2

1. 有序列表项1
2. 有序列表项2

> 引用块，用来放名言、备注、吐槽

[跳转链接](https://polynyablog.dpdns.org)

:::note
普通提示，比如「注意备份配置」
:::

:::tip
小技巧，比如「可以用pnpm dlx代替npx节省空间」
:::

:::warning
警告，比如「修改NS前先备份原有配置」
:::

:::important
重要提醒，比如「部署前务必本地build验证」
:::

:::caution
危险操作，比如「删除数据库前确认备份」
:::

<!-- 还可以自定义标题 -->
:::note[我的自定义提示]
内容支持**加粗**、`行内代码`等Markdown语法
:::

::github{repo="1nkoraMeow/fuwari"}

这是正文内容[^1]

[^1]: 这是脚注内容，会显示在文章末尾