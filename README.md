# 模力枢纽 · Model Route Hub

**发现模型，验证方案，连接算力。**

面向开发者的中文 AI 模型与计算资源导航。把分散的模型 API、GPU / CPU 服务和 Token 工具整理到同一个工作台：从官方资料开始选型，在浏览器里试问真实模型，再生成接入示例、估算使用成本。

[**进入工作台 ↗**](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/) · [免费试问真实模型](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#free-lab) · [阅读选型指南](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/guides/choose-api-gpu-cpu.html)

---

## 从发现到接入

| 环节 | 你可以做什么 |
| --- | --- |
| **发现资源** | 按模型 API、GPU、CPU、Token 工具分类浏览，搜索服务商并直达官方文档与价格页。 |
| **体验模型** | 在支持 WebGPU 的浏览器中，向 Qwen2.5 1.5B 真实模型免费试问两次；回答在本机生成。 |
| **规划接入** | 为支持 OpenAI 兼容接口的服务商生成 Python、JavaScript、cURL 或 PowerShell 起步代码。 |
| **估算成本** | 输入实际单价与请求量，粗估 Token 支出；也可使用提示词、Token 长度和显存估算工具。 |

目前收录 **27 个资源**：13 个模型 API、6 个 GPU 服务、4 个 CPU 服务和 4 个 Token 工具。目录支持筛选、搜索与浏览器本地收藏。资源数量截至 2026-10-16，持续维护中。

## 60 秒开始使用

1. 打开[资源目录](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#catalog)，按任务选择模型 API、GPU 或 CPU，并核对服务商官方资料。
2. 到[免费体验区](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#free-lab)试问模型，或用小工具估算提示词与算力需求。
3. 在[路由配置生成器](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#builder)创建接入示例；密钥由你自行在本机环境中管理。

## 关于免费模型体验

体验区使用 [Qwen2.5-1.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct) 和 [WebLLM](https://github.com/mlc-ai/web-llm) 在访客设备上运行真实模型，不调用本站托管的模型 API，也不需要共享 API Key。每个浏览器本地记录两次试问；清理浏览器数据可重置，**这不是账号级配额或防刷机制**。

首次使用需下载约 800 多 MB 模型文件，且浏览器与设备须支持 WebGPU。它适合体验交互流程，不应代替云端大模型的质量评测；重要回答请自行核实。

## 收录与反馈

优先收录有官方文档、清晰入口和可核对服务条件的资源。价格、免费额度、地区与条款会变化，最终以服务商官方资料为准。欢迎在 [Issues](https://github.com/notquitezero-ai/model-route-hub/issues/new) 推荐资源、报告失效链接或提出合作建议；请附官方来源，勿提交 API Key 或保密报价。

本仓库用于项目介绍与公开反馈。模力枢纽目前是独立资源索引：目录链接不是专属返佣链接，与所列服务商没有合作关系；本站不销售 Token 或算力，不代理付费 API 请求，也不代收服务商费用。
