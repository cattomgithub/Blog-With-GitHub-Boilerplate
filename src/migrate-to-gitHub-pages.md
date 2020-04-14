---
layout: post
title: 博客现已迁移至 GitHub Pages
slug: migrate-to-gitHub-pages
date: 2020-04-07 18:50
status: publish
author: Cat Tom
categories: 
  - 随笔
tags: 
  - 搬家
excerpt: 对，没错。时隔一个月，我又搬家了。
---
## 我又搬家了
对，没错。

时隔一个月，我又搬家了。

这一次选择抛弃使用多年的 WordPress，加入了静态博客的队伍。目前采用了 [Maverick](https://github.com/AlanDecode/Maverick) 作为静态页面生成器。
以后可能会考虑采用 Hexo。

目前通过 GitHub Pages 托管在 `gh-pages` 分支中。CI 服务由 [GitHub Actions](https://github.com/features/actions) 提供。CDN 服务由 [jsDelivr](https://www.jsdelivr.com/) 提供

 在这里分享 jsDelivr 官网上的一句话：
 > jsDelivr is the only public CDN with a valid ICP license issued by the Chinese government, and hundreds of locations directly in Mainland China.

所以，我基本上不需要考虑大陆地区连接的速度问题了，[Maverick](https://github.com/AlanDecode/Maverick) 可以自动将文件中的元素链接到 jsDelivr 上。
## 抛弃传统博客
虽然 WordPress 的功能非常全面，但未免有些繁多。

对于像我这样的只想一心一意专心码子的博主来说未免还是太麻烦了。

而且古腾堡编辑器真的感觉...不太好

从前觉得 MarkDown 麻烦，现在感觉也挺好的。

而且现在将源文件放在 GitHub 上，还能直接利用 GitHub Pages 托管网站，相比以前，别提有多爽了。
## 最近的计划
![](./images/migrate-to-gitHub-pages-001.png)
在 `In progress` 内的是最近想写的。（当然可能会咕咕咕