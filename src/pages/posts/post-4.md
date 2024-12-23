---
layout: ../../layouts/MarkdownPostLayout.astro

title: 我的第四篇博客文章
author: Astro 学习者
description: "这篇文章会自己出现在列表中！"
image:
    url: "https://docs.astro.build/assets/rays.webp"
    alt: "The Astro logo on a dark background with rainbow rays."
pubDate: 2022-07-15
tags: ["astro", "learning in public", "setbacks", "community"]
---
这篇文章应该会与其他的博客文章一起显示，因为 `Astro.glob()` 会返回一个包含所有文章的列表，以创建这个文章列表。
