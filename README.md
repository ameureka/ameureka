<!---
- 👋 Hi, I’m Ameureka ,
- 👀 I’m interested in AI
- 🌱 I am currently working in the field of cloud computing and generative artificial intelligence.
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
ameureka/ameureka is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## 👋 Hi，我是 Ameureka ！

[中文](README.md) | [English](README.en.md)

  ![IMG plateoperating](https://github.com/ameureka/ameureka/blob/main/files/Ameureka%20AI%20Agent%20Architect.png)
- 我关注如何把大模型能力组织成可验证、可复用的工作流，并接入产品与业务交付。我的实践覆盖 LLM 微调、多智能体研究、图像与视频生成、全栈应用，以及 AI 辅助研发。
近期，我把这些实践集中到三件事上：约束 Agent 的执行过程、让研究结论能够追溯证据、把专业知识转化为可复用的工具与交付流程。

## 🏆 **代表项目**

| 项目 | 解决的问题 | 工程重点 |
| --- | --- | --- |
| [**open-source-ssd**](https://github.com/ameureka/open-source-ssd) | 如何验收 AI 编程助手的交付 | Harness Engineering、规格驱动开发、全栈脚手架 |
| [**present-waza-agent**](https://github.com/ameureka/present-waza-agent) | 如何把分散材料变成可上台的技术演讲 | 叙事与页级规格、PPTX 工具、评分与彩排 |
| [**open-waza-agent**](https://github.com/ameureka/open-waza-agent) | 如何把研究过程变成有证据、可审阅的报告 | 证据契约、版本修订、质量检查、Word 交付 |
| [**ameureka-skills**](https://github.com/ameureka/ameureka-skills) | 如何复用 AI 协作中的方法与工具 | 7 个工作流 Skills、2 个独立 CLI 工具 |

## 🏘️ 01 · AI 研发全栈工程化 — open-source-ssd

  ![IMG plateoperating](https://github.com/ameureka/ameureka/blob/main/files/Reliable%20AI%20Delivery.png)
- 把内容规划、品牌规划、审计、需求矩阵、长任务执行与规格实施连接起来，为 AI 编程提供明确的输入、产物和验收条件。
- 流程设计 🎭 —— 任务拆解、停止条件、设计规范与发布 Runbook，让开发和交付有可追踪的依据。
- 工程实现 🛠️ —— Next.js / TypeScript 全栈模板，配合检查配置、Server Action 边界、依赖与国际化资源的门禁脚本。
- 经验沉淀 🤝 —— 公开工程复盘、架构图和交互式流程图，记录机制设计与实际落地之间的差距。
- [全栈模板](https://github.com/ameureka/open-source-ssd/tree/main/template) · [门禁实现](https://github.com/ameureka/open-source-ssd/blob/main/template/scripts/check-gates.mjs) · [工程实践复盘](https://github.com/ameureka/open-source-ssd/blob/main/article/Harness-Engineering-%E5%AE%9E%E8%B7%B5.md)

## 🏘️ 02 · 技术表达与交付 — present-waza-agent

  ![IMG plateoperating](https://github.com/ameureka/ameureka/blob/main/files/Ideas%20to%20Keynotes.png)
- 将技术演讲拆成材料结构化、叙事设计、页级规格、版本打磨与上台准备，形成可供 Agent 使用的交付流程。
- 知识组织 🎭 —— 先确定核心主张与证据，再设计每页的论点、视觉表达和口播内容。
- 交付工具 🛠️ —— 基于 Python / python-pptx 提供构建与合并工具，以及 PPTX 审计、评分汇总和提词器生成脚本。
- 质量机制 🤝 —— 回归用例覆盖 CLI 退出码、输入保护、分页和合并；CI 配置覆盖三个操作系统与两个 Python 版本。
- [合成案例](https://github.com/ameureka/present-waza-agent/blob/main/examples/synthetic-case-iot-identity-keynote.md) · [交付脚本](https://github.com/ameureka/present-waza-agent/tree/main/skills/keynote-pipeline/scripts) · [测试与 CI](https://github.com/ameureka/present-waza-agent/blob/main/.github/workflows/test.yml)

  
## 🏘️ 03 · 研究工作流与证据管理 — open-waza-agent

  ![IMG plateoperating](https://github.com/ameureka/ameureka/blob/main/files/Evidence%20to%20Insight.png)
- 把问题定义、证据整理、论证修订和文档交付组织成一条可检查的研究流程。
- 证据建模 🎭 —— 显式记录来源、论断、交付物和修正，用版本与文件哈希绑定审阅内容。
- 自动化边界 🛠️ —— 研究由人或宿主 Agent 执行；Python 工具负责证据登记检查、文本质量检查、章节合并与 Word 导出。
- 可复现入口 🤝 —— 提供离线合成示例、失败路径测试，以及保护人工 Word 修订的流程。
- [证据契约](https://github.com/ameureka/open-waza-agent/blob/main/docs/evidence.md) · [完整合成示例](https://github.com/ameureka/open-waza-agent/tree/main/examples/full-report) · [回归测试](https://github.com/ameureka/open-waza-agent/tree/main/tests)

## 🏘️ 04 · Agent Skills 与开发工具 — ameureka-skills

  ![IMG plateoperating](https://github.com/ameureka/ameureka/blob/main/files/Reusable%20Agent%20Skills.png)
- 把项目中反复使用的推理、审计、规格与协作方法整理为可组合的 Skills，并配套独立工具。
- 7 个 Skills 🎭 —— 规格驱动开发、盲区审计、需求矩阵、第一性原理推理、长任务提示词、企业架构图与 Agent 交接。
- 2 个 CLI 工具 🛠️ —— 图像生成客户端 `gpt-imageflow`，以及带截图检查与报告的 HTML → PPTX 工具链 `present-met-ppt-kit`。
- 复用设计 🤝 —— 明确每个工作流的输入输出、停止条件、外部依赖和使用边界。
- [Skills 目录](https://github.com/ameureka/ameureka-skills/tree/main/skills) · [图像工具](https://github.com/ameureka/ameureka-skills/tree/main/tools/gpt-imageflow) · [PPTX 工具链](https://github.com/ameureka/ameureka-skills/tree/main/tools/present-met-ppt-kit)

## 🏛️ **职业**
- 架构师 | 云计算与AIGC

## ❣️ **兴趣**
- AIGC
- 大模型LLM&理论 | 实用主义 ✅ 
- 产品 | 第一性原理 ✅
- 商业化 | 先进生产工具x先进生产关系 ✅ 

## 🔥 **更广的AI实践**

| 方向 | 项目与实践 |
| --- | --- |
| **多智能体与全栈应用** | [ai-deepresearch-agent](https://github.com/ameureka/ai-deepresearch-agent)：规划、研究、写作与编辑角色协作；Next.js + FastAPI、SSE 进度反馈、模型适配与回退。 |
| **LLM 微调与本地推理** | [Unsloth_Lllama_deepseek](https://github.com/ameureka/Unsloth_Lllama_deepseek)：围绕 Llama 3.1 8B 的数据准备、微调、推理、模型保存与 Ollama 导出实践。 |
| **多模态应用** | [nano-bananary-playground](https://github.com/ameureka/nano-bananary-playground)：基于 Next.js / React / Gemini 的图像与视频生成应用，覆盖生成、编辑与资产管理。 |
| **产品与商业化研究** | [Product_Co_Meth](https://github.com/ameureka/Product_Co_Meth)：整理企业场景的 MVP 验证、LLM 产品价值与开源商业模式分析。 |

这些工程实践也延续了我在 **ComfyUI、Stable Diffusion / LoRA、AIGC 图像与视频创作、教程与知识整理**方面的积累。我习惯把探索过程留下来，整理成后来可以复查、复用的方法与代码。

## 🌟 **技术与工作方式**
- Agent 工程：工作流编排、工具调用、Skills、规格驱动开发、证据与验收设计。
- 应用开发：Python、TypeScript、Next.js / React、FastAPI、PostgreSQL、Docker、Vercel。
- 模型与生成：LLM 微调、Unsloth / Ollama、ComfyUI / LoRA、多模态 API 集成。
- 我重视三个工程习惯：把需求写成可验收的约定；把结论关联到代码、来源或运行结果；把复盘转成下一次可以执行的检查与流程。

## 📬 **联系我**：
- 欢迎交流 AI / Agent 架构、研发工具链与生成式 AI 应用落地。
- 邮箱：slicesarah8@gmail.com



