# 模力枢纽 · Model Route Hub

**发现模型，验证方案，连接算力。**

模力枢纽是面向开发者的中文 AI 模型与算力资源导航。你可以在一个工作台中查找模型 API、GPU / CPU 服务和 Token 工具，免费试问真实模型，生成接入配置，并估算使用成本。使用资源目录和模型试问无需注册。

[进入工作台 ↗](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/) · [免费模型试问](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#free-lab) · [阅读选型指南](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/guides/choose-api-gpu-cpu.html)

## 可以做什么

| 功能 | 说明 |
| --- | --- |
| 资源目录 | 浏览 27 项模型 API、GPU、CPU 和 Token 资源；按类别筛选、搜索、收藏，并前往服务商官方文档。 |
| 本地 Qwen2.5 | 在支持 WebGPU 的浏览器中运行 0.5B、1.5B 或 Coder 1.5B；不限试问次数，不消耗云端额度。 |
| 云端免费试问 | 在本站选择当前免费的云端模型直接提问，无需跳转或登录；每个浏览器最多获得两次成功回答。 |
| 接入与估算 | 生成 Python、JavaScript、cURL、PowerShell 接入示例，并粗估 Token 费用、提示词长度和模型权重显存。 |

目前收录 **27 项资源**：13 个模型 API、6 个 GPU 服务、4 个 CPU 服务、4 个 Token 工具。资源数量截至 2026-10-16；价格、免费额度和可用地区请以服务商官方页面为准。

## 免费试问如何工作

**本地 Qwen2.5：**模型在访客设备上运行，不限试问次数，也不消耗本站云端额度。首次使用需下载模型文件，要求浏览器支持 WebGPU 且设备有足够内存。加载中可以暂停、继续，未下载完的部分可能重新下载。

**云端模型：**本站后端通过 OpenRouter 调用实时标记为免费的模型，访客不用提供 API Key。当前默认选择已实测可回答的 Cohere 免费型号；可选模型会变化，DeepSeek、Qwen、Gemma 等只有在符合免费条件时才会出现。每个浏览器最多获得两次成功回答；上游失败不扣这两次额度。为控制共享资源，每个 IP 每日最多发起六次请求，全站每日最多四十次请求。免费模型可能限流、暂停或下线。问题会发送给所选模型的服务方处理，重要回答请自行核实。

## 开始使用

1. 打开[资源目录](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#catalog)，按任务选择模型 API、GPU 或 CPU，并核对官方资料。
2. 到[免费体验区](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#free-lab)选择不限次数的本地 Qwen2.5，或使用有限云端试问。
3. 在[路由配置生成器](https://model-route-hub-chen-20261016.nutty-wren-8644.chatgpt.site/#builder)创建接入示例；自己的付费 API Key 请自行保管。

## 收录与反馈

优先收录有官方文档、清晰入口和可核对服务条件的资源。欢迎通过 [GitHub Issues](https://github.com/notquitezero-ai/model-route-hub/issues/new) 推荐资源、报告失效链接或提出合作建议；请附官方来源，不要提交 API Key 或保密报价。

本仓库用于项目介绍与公开反馈。目录链接目前不是专属返佣链接，本站与所列服务商没有合作关系；本站不销售 Token 或算力，不代理访客自备密钥的付费 API 请求，也不代收服务商费用。限量免费试问由本站后端提供。
