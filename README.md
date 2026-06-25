# Agent Tool Bench

AI agent 工具评测开源项目。

## 项目目标

构建一套可复现、可解释、可持续更新的评测框架，用来比较 AI agent 工具在真实任务中的表现。

## 初始范围

- 定义评测维度和评分方法。
- 定义工具适配器接口。
- 定义评测任务和样例数据集。
- 生成本地评测报告。
- 将评测结果同步到信息网站。

## 计划目录

| 路径 | 用途 |
|------|------|
| `evals/` | 评测任务、场景、期望结果 |
| `datasets/` | 公开样例数据 |
| `packages/` | 未来核心库、CLI、工具适配器 |
| `docs/` | 开源项目文档 |
| `apps/site/` | 可选的评测报告应用 |

## 评测维度草案

- Task success
- Reliability
- Controllability
- Observability
- Cost and latency
- Integration experience
- Safety boundary
- Reproducibility

## 开源发布前必须确认

- License: 选择 MIT、Apache-2.0 或其他适合的开源协议。
- Contribution: 补充贡献指南、Issue 模板和 PR 模板。
- Reproducibility: 每个公开评测都必须说明环境、输入、评分规则和复现步骤。
- Safety: 不提交私有代码、账号信息、平台后台截图或未授权数据。
- Scope: 保持本目录聚焦评测框架，不放自媒体草稿或付费课程正文。
