---
title: "Daily News #2025-06-11"
date: "2025-06-11 23:25:25"
description: "WWDC 2025开发者初印象：稳定更新与AI融合新进展
苹果悄悄推出的macOS Ventura新功能ExtensionKit解析
逆向解析iPhone语音备忘录转录文本：.m4a文件格式深度揭秘
跨库查询数据的实用工具实现
SGLang：开源推理引擎的性能与成本突破
地瓜机器人RDK S100：单SoC赋能具身智能新发展
Expert Swift：深入掌握Swift高级特性与开发技巧
Swift 6.2中如何使用#Playground宏优化代码调试"
tags: 
- "工具开发"
- "Swift开发"
- "文件格式"
- "macOS开发"
- "数据库"
- "边缘计算"
- "开源技术"
- "机器人开发"
- "SwiftUI 更新"
- "大模型推理"
- "SQL"

---

> - WWDC 2025开发者初印象：稳定更新与AI融合新进展
> - 苹果悄悄推出的macOS Ventura新功能ExtensionKit解析
> - 逆向解析iPhone语音备忘录转录文本：.m4a文件格式深度揭秘
> - 跨库查询数据的实用工具实现
> - SGLang：开源推理引擎的性能与成本突破
> - 地瓜机器人RDK S100：单SoC赋能具身智能新发展
> - Expert Swift：深入掌握Swift高级特性与开发技巧
> - Swift 6.2中如何使用#Playground宏优化代码调试

## 🍎 iOS Blog

### [WWDC 2025开发者初印象：稳定更新与AI融合新进展](https://fatbobman.com/zh/posts/wwdc-2025-first-impressions/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2025-06-11 08:12:00

本文总结WWDC 2025开发者大会的核心内容，指出苹果此次更新以稳定性与实用性为主。重点提及SwiftUI新API与Liquid Glass适配挑战、SwiftData修复关键Bug及模型继承功能、Foundation Models通过@Generable宏实现端侧AI应用简化。作者认为苹果虽未在大模型训练上领先，但凭借生态优势在应用AI融合领域取得突破，并期待Xcode Playground的即时交互功能提升开发效率。整体评价为意料之中但超出预期，认为苹果交出了令人满意的答卷。

### [苹果悄悄推出的macOS Ventura新功能ExtensionKit解析](https://www.massicotte.org/extensionkit-intro)

来源：massicotte.org

发布时间：2025-06-11 08:00:00

ExtensionKit是苹果在macOS Ventura中引入的重要扩展框架，用于增强系统功能的灵活性和可定制性。尽管其功能意义重大，但苹果在发布时采取了非常低调的策略，未在WWDC 2022活动中安排相关技术分享或实验室。作者通过朋友提供的beta文档意外了解到该技术，暗示其可能在开发者群体中存在较高的使用价值，但因官方宣传不足导致大众认知度较低。该框架体现了苹果对系统级开发的持续探索，值得关注其未来在macOS生态中的应用潜力。

## 📥 Tech News

### [逆向解析iPhone语音备忘录转录文本：.m4a文件格式深度揭秘](https://thomascountz.com/2025/06/08/unlocking-apple-voice-memo-transcripts)

来源：Hacker News - Newest: "apple"

发布时间：2025-06-11 20:19:53

作者通过逆向工程发现Apple Voice Memos的转录文本以JSON格式嵌入.m4a文件的tsrp原子中。文章详解了ISO/IEC 14496-17标准的文本流编码机制，并展示如何利用strings、rg、sed、jq等工具提取转录数据。分析指出语音备忘录文件采用分层的atom结构存储多媒体信息，其中tsrp原子未被官方文档说明。尽管技术细节复杂，但作者提供了Ruby脚本和bash命令实现转录提取，为开发者探索封闭系统文件格式提供了实践案例。

### [跨库查询数据的实用工具实现](https://www.v2ex.com/t/1138017)

来源：V2EX-最新主题

发布时间：2025-06-11 23:01:09

开发者为解决跨库查询需求，创建了将多行查询结果自动转换为SQL IN子句的工具。通过具体示例展示如何将用户名列表转换为可直接使用的SQL语句，解决了手动拼接的繁琐问题。该工具适用于需要处理多源数据的场景，同时提供了替代方案的思考，对数据库操作有实际参考价值。

### [SGLang：开源推理引擎的性能与成本突破](https://www.infoq.cn/article/dWT6bw3Mh76rfS5Hu0kK)

来源：InfoQ 推荐

发布时间：2025-06-11 17:20:55

SGLang作为开源推理引擎，凭借高性能实现和易二次开发特性，被xAI、微软Azure、英伟达等企业采用。其核心优势包括PD分离架构降低尾延迟、推测解码提升Token生成速度、KV缓存落盘优化显存占用。开发者可通过调整部署策略平衡性能与成本，例如离线批处理注重显存利用率，线上推理优先保障响应速度。SGLang社区通过开源协作与工业实践反馈，推动技术持续迭代，帮助开发者高效部署DeepSeek等大模型。

### [地瓜机器人RDK S100：单SoC赋能具身智能新发展](https://www.infoq.cn/article/AvWdYPO1rizXjymA05NK)

来源：InfoQ 推荐

发布时间：2025-06-11 17:10:57

地瓜机器人发布行业首款单SoC算控一体化开发套件RDK S100，采用类人大小脑异构架构，集成CPU+BPU+MCU三核芯片，实现感知-决策-控制闭环。其'大脑'支持复杂决策，'小脑'确保实时运控，可动态切换大小模型提升效率。配套全链路开发工具链和200+开源示例，已获50+客户测评。2026年将推出更多大算力产品，加速具身智能场景落地。

## 💾 Daily Dev

### [Expert Swift：深入掌握Swift高级特性与开发技巧](https://www.kodeco.com/books/expert-swift)

来源：iOS Development News - Telegram Channel

发布时间：2025-06-11 18:32:48

《Expert Swift》是一本面向中级Swift开发者的进阶书籍，系统讲解了Swift语言的核心特性与高级应用。全书分为三部分：第一部分涵盖类型系统（枚举、结构体、类）、协议与泛型等基础构建块；第二部分深入解析标准库的底层实现，包括数值类型、范围操作、字符串处理、编码解码等；第三部分聚焦高阶技术，如函数式编程、API设计、Objective-C互操作性等。作者团队由资深开发者和编辑组成，内容注重实际应用与底层原理，适合希望全面掌握Swift进阶知识的开发者。

### [Swift 6.2中如何使用#Playground宏优化代码调试](https://onmyway133.com/posts/how-to-use-playground-in-swift-file/)

来源：iOS Development News - Telegram Channel

发布时间：2025-06-11 16:52:28

本文介绍Swift 6.2新增的#Playground宏，允许开发者在普通Swift文件内嵌入可执行代码块，突破传统Playground的限制。通过该宏，可在同一文件中测试私有函数，并利用Assistant面板查看执行流程。文章还简要提及iOS 18的其他新特性，如Liquid Glass视图过渡和widget配置引导，但核心聚焦于#Playground宏的实际应用案例与优势，为开发者提供了更灵活的调试方案。

