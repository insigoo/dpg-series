# insigoo DPG Series

**面向公益行业的数字公共品（Digital Public Goods）——开源、可复算、可共评的评估标准与知识工具。**

> 我们的核心战略：将通用行业知识标准化、将标准技术化、将技术工程化、将工程开源化。
> 标准不只是一份文档，而是 AI agent 能理解、能执行、能被真实案例反复校准的机器标准。

## 这是什么

DPG Series 是一套面向公益行业的开源基础设施。它把散落在监管要求、国际评估方法、行业评审实践里的知识编译成统一标准，再把标准做成可运行、可复算、可贡献的工程工具。

每个组件独立可用，无私有依赖。全部 MIT 开源、免费、可离线运行、无付费墙。

## 组件清单

| 组件 | 定位 | 当前状态 | 仓库 |
|---|---|---|---|
| **SIA** | 标准层 · 社会影响力评估 | v3.4.0；L1/L2 已通过真实项目验证；L3 为草案（1 个端到端案例）；D 线早期 | [insigoo-sia-open](https://github.com/insigoo/insigoo-sia-open) |
| **SAG Architect** | 知识层 · 组织知识库架构 | 已开源，架构师工具（建库 / 编译 / 诊断） | [insigoo-sag-architect](https://github.com/insigoo/insigoo-sag-architect) |
| **SIA 100 快检报告** | 基线数据 · 逐项证据与统计脚本 | 100 项目快检数据公开，可一键复算 | [sia-100-report](https://github.com/insigoo/sia-100-report) |
| **SIA 200 信度检验报告** | 方法学数据 · 信度检验与复算脚本 | 200 项目全量双人重判，一致率 84.15% REVIEW；脱敏报告与聚合数据公开，publishable=false、不排序 | [sia-200-report](https://github.com/insigoo/sia-200-report) |
| **Data Agent** | 应用层 · 智能数据助手框架 | 准备开源（长期运行于真实业务环境） | 尚未发布，关注本仓更新 |
| **成熟度自测** | 入口层 · 组织数智化五级自评 | 准备开源 | 尚未发布，关注本仓更新 |

## 贡献入口

我们希望每一个真实案例都能按同一套技术和工程标准，贡献、丰富、校准已有的标准。

| 你想做的事 | 去哪里 |
|---|---|
| 修改评分锚点、评估方法、L1 / L2 / L3 / D 线标准 | [insigoo-sia-open](https://github.com/insigoo/insigoo-sia-open) |
| 提交快检复算结果、新快检判例与统计口径 | [sia-100-report](https://github.com/insigoo/sia-100-report) |
| 提交批量信度检验、双人重判与方法学复现 | [sia-200-report](https://github.com/insigoo/sia-200-report) |
| 改进知识库治理标准、SAG 架构与编译规则 | [insigoo-sag-architect](https://github.com/insigoo/insigoo-sag-architect) |
| 参与成熟度自测表、Data Agent 与贡献 skill | 尚未发布，关注本仓更新 |

提交 PR 前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)，并遵守 [行为准则](CODE_OF_CONDUCT.md)。

## 关于 DPG

DPG Series 对标 Digital Public Goods 标准（MIT 开源、可离线、无付费墙）。DPGA registry 注册在计划中，尚未完成。

## 联系

- 维护者：俞潮（insigoo）
- 邮箱：insigoo@insigoo.cn
- 讨论与提议：欢迎通过各组件仓库的 Issue 与 PR 交流。
