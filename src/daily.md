---
layout: page
title: 碎碎念
slug: daily
date: 2020-04-15 10:00
status: publish
author: Cat Tom
categories: 
  - 页面
---

# 2020 年
## 4 月 16 日
今天搞了一台阿里云国际的ECS，香港区，配置是1C、1G、1M(Mbps)，用来做网站绰绰有余了。

而且价格挺优惠的，只需要60元/年（我是找代购的
## 4 月 15 日
早上：今天搞了张虚拟卡，准备去薅羊毛😏

晚上：翻车了🌚

我就脱圈几个月，风控就变严了...

算了算了，不说了，都是辛酸泪😭

## 4 月 12 日
### 运气？！
周日晚上考了语文，难度有点大，成绩自然是惨不忍睹的。

考试结束后，到处问了一下成绩，大多成绩都不太好。

这时，lwt出现了！

![](./images/daily-007.jpg)

![](./images/daily-006.jpg)

我们当时都很怀疑，怎么可能蒙对 10 道选择题，
然后他接着说...

![真是要气死我了！！！](./images/daily-005.jpeg)
### 运气！！
后来，我提议lwt去买彩票。

以下是对话原文（大概）：
 > lwj：你这个“蒙”，比看书本查答案还要准确啊...
 > 
 > 我建议你今晚别洗手了，赶紧去买张彩票吧，搞不好就中大奖了...
 >
 > lwt：你还别说，我刚刚去剪头发，和我老爸顺便买了一张

然后，他还真的中奖了！便有了以下这一幕...

![也许，这就是欧皇吧...](./images/daily-008.jpeg)
## 4 月 11 日
最近在白嫖 Azure，到时候可能会出教程。

和 Azure 的客服小姐姐打交道好困难啊！！！

![](./images/daily-004.jpg)
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
