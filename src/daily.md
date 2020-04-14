---
layout: page
title: 碎碎念
slug: daily
date: 2020-04-08 11:50
status: publish
author: Cat Tom
categories: 
  - 页面
---

# 2020 年

## 4 月 10 日
最近在白嫖 Azure，到时候可能会出教程。

和 Azure 的客服小姐姐打交道好困难啊！！！
## 4 月 10 日
### 奇 思 妙 想
昨天晚上睡觉前，想到博客都迁移到了 Github Pages 上，不如将部署在阿里云香港的其他网站也迁移到过来吧。

这样子做的话，好处有：
 - 减轻阿里云香港的负担（毕竟它只是一个1C1G的小鸡啊）
 - 充分利用 Git 的版本控制特性

但是早上起来，我突然间想起来 GitHub Pages 只支持静态网页...

![](./images/daily-001.jpg)

然后我检查了一下我的部署架构图，
发现只有 [Start](https://start.cattom.space/)、[Navigation](https://cattom.space/)、[Music](https://music.cattom.space/) 三个网站是静态网站，于是便一口气将他们全部丢上 GitHub 上了。

丢上去之后都做了自定义域，但到启动 HTTPS 之后，
访问的时候 Chrome 提示我证书错误？！

然后，GitHub 提示我 DNS 解析失败...

![](./images/daily-002.jpg)

然后我用 `dig` 检查了一下，发现解析正常。

然后过了一阵子之后，就恢复正常了...

![](./images/daily-003.jpg)
## 4 月 8 日
最近看到[熊猫小A](https://blog.imalan.cn/)大佬的[完全使用 GitHub 写博客](https://blog.imalan.cn/archives/blog-with-github/)，而且还有范例仓库，便 fork 下来尝试一下。

这个博客目前是利用 GitHub Pages 托管静态网页，GitHub Action 自动构建、发布文章。

MarkDown 还是很有意思的。

以后可能会考虑将[原博客](https://cattom.site)里的文章搬移到这里。
