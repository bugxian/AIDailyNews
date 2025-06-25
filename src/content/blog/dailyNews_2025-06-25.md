---
title: "Daily News #2025-06-25"
date: "2025-06-25 23:24:23"
description: "Swift 6.2并发安全通知机制详解：NotificationCenter.Message全面解析
苹果激烈反对法院对App Store的惩罚性裁决
Google Gemini CLI开源AI代理工具上线
SwiftSoup：跨平台HTML解析库的高效用法与安全特性
Swift 6.2迁移教程：并发简化与数据隔离域详解"
tags: 
- "HTML解析"
- "AI技术"
- "迁移指南"
- "并发编程"
- "企业策略"
- "法律纠纷"
- "Swift"
- "安全"
- "开源工具"

---

> - Swift 6.2并发安全通知机制详解：NotificationCenter.Message全面解析
> - 苹果激烈反对法院对App Store的惩罚性裁决
> - Google Gemini CLI开源AI代理工具上线
> - SwiftSoup：跨平台HTML解析库的高效用法与安全特性
> - Swift 6.2迁移教程：并发简化与数据隔离域详解

## 🍎 iOS Blog

### [Swift 6.2并发安全通知机制详解：NotificationCenter.Message全面解析](https://fatbobman.com/zh/posts/notificationcentermessage-a-new-concurrency-safe-notification-experience-in-swift-62/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2025-06-25 22:00:00

本文深入解析Swift 6.2中引入的NotificationCenter.Message并发安全通知系统，重点介绍了MainActorMessage和AsyncMessage两个核心协议。该机制通过类型系统和并发隔离特性，实现在编译期验证通知的线程安全性和数据类型正确性，有效解决传统通知在多线程环境中可能引发的崩溃问题。文章提供了具体代码示例，演示如何定义消息类型、实现协议转换以及在SwiftUI中的自定义集成方案。同时包含迁移建议和与旧版API的兼容性说明，适合Swift 6.2开发者探索更安全的并发通知实践。

## 📥 Tech News

### [苹果激烈反对法院对App Store的惩罚性裁决](https://9to5mac.com/2025/06/24/apple-fires-back-at-courts-punitive-app-store-order-in-epic-games-case/)

来源：Hacker News - Newest: "apple"

发布时间：2025-06-25 17:08:29

苹果针对Epic Games案中法院的裁决提出上诉，认为新颁布的禁令无法律依据且构成惩罚，要求案件重新分配给其他法官。法院此前下令苹果不得收取应用内购买的佣金，并限制其对支付渠道的管控。苹果反驳称该裁决违反加州不公平竞争法，并强调异议应基于现有命令而非新增条款。评论指出苹果曾多次被判定违反禁令却拒不执行，凸显其法律争议。

### [Google Gemini CLI开源AI代理工具上线](https://www.v2ex.com/t/1141070)

来源：V2EX-最新主题

发布时间：2025-06-25 22:54:41

Google官方推出Gemini CLI开源项目（GitHub: https://github.com/google-gemini/gemini-cli），提供基于Google账号的API调用配额（每分钟60次/每天1000次），内置搜索和网页访问功能。但存在无故退出和部分账号登录异常等已知问题。

## 💾 Daily Dev

### [SwiftSoup：跨平台HTML解析库的高效用法与安全特性](https://github.com/scinfu/SwiftSoup)

来源：iOS Development News - Telegram Channel

发布时间：2025-06-25 10:12:20

SwiftSoup是一款纯Swift编写的HTML解析库，支持macOS、iOS等多平台，提供类似jQuery的CSS选择器和DOM操作功能。其核心优势包括对脏数据的智能处理、防止XSS攻击的白名单机制，以及符合WHATWG HTML5规范的解析能力。文章详细说明了通过CocoaPods、Carthage和Swift Package Manager的安装方式，并附有文本提取、元素修改等使用案例，适合需要处理网页数据的开发者快速上手。

### [Swift 6.2迁移教程：并发简化与数据隔离域详解](https://www.kodeco.com/48297451-migrating-to-swift-6-tutorial)

来源：iOS Development News - Telegram Channel

发布时间：2025-06-25 23:07:21

这篇文章深入讲解了Swift 6.2的并发改进，重点介绍了从单线程到并发模型的转变，以及通过async/await、async let等关键词简化开发流程。内容涵盖数据隔离域机制，旨在消除数据竞争，强调使用let和值类型（如struct）的重要性。文中还提供了TheMet应用的迁移示例，展示了如何在Xcode 26中逐步启用Swift 6检查，并验证后台线程执行方法。适合iOS开发者了解Swift 6的新特性和迁移实践。
