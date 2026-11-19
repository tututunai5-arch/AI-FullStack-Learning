# AI Full-Stack Learning

我的长期 AI 全栈学习工作区。通过中文开源教材、真实项目和持续实践，逐步具备独立设计、开发、测试、部署和维护完整 AI 系统的能力。

## 最终目标

不仅会调用模型 API，还能独立完成一个 AI 产品的完整工程过程：

- 理解需求、用户场景和系统边界；
- 设计前后端、数据库、模型服务和数据流；
- 构建 LLM、RAG、Agent 和 MCP 应用；
- 编写测试、评估模型质量、排查故障；
- 部署、监控、保护数据并控制成本；
- 解释技术选择、局限和改进方向。

## 学习者与学习安排

- Python：入门阶段
- 数学：有基础，需要结合项目逐步补强
- 英语：可以阅读技术资料，中文讲解优先
- 每日投入：约 2 小时
- 学习方式：项目驱动，理论与实践结合
- 主要设备：MacBook；辅助设备：Windows 11

路线规划为 48 周，每周建议学习 6 天、休息或补进度 1 天。它是参考节奏，不是硬性期限；阶段验收未通过时，先补足再继续。

## 工具分工

| 工具 | 主要职责 |
|---|---|
| GitHub | 在线阅读开源教材、保存代码和学习记录、管理版本 |
| VS Code | 编辑代码、运行程序、管理项目 |
| Codex 扩展 | 阅读当前项目、解释代码、辅助调试、代码审查和测试 |
| ChatGPT | 学习规划、概念讲解、疑难讨论、阶段复盘和验收 |
| MacBook / Windows 11 | 两套独立开发环境，通过 Git 同步源码和 Markdown |

学习原则：先自己思考和尝试，再让 AI 提示、解释和检查；关键代码必须能由我自己讲清楚。

## 48 周学习路线

| 阶段 | 周数 | 核心内容 | 项目成果 |
|---|---:|---|---|
| 1. Python 与开发基本功 | 1–6 | Python、Git、HTTP、API、测试 | 命令行学习助手 |
| 2. 数学与数据处理 | 7–10 | NumPy、Pandas、统计、梯度直觉 | 数据分析报告 |
| 3. 机器学习 | 11–16 | 回归、分类、聚类、评估 | 端到端预测/分类项目 |
| 4. 深度学习 | 17–22 | PyTorch、神经网络、Attention、Transformer | 可训练和评估的模型 |
| 5. LLM | 23–28 | Token、Transformer、推理、模型 API | 多模型聊天应用 |
| 6. RAG | 29–34 | 文档处理、Embedding、检索、评估 | 个人知识库问答系统 |
| 7. Agent 与 MCP | 35–40 | Tool Calling、工作流、Memory、MCP | 可控的研究/任务助理 |
| 8. 全栈工程与部署 | 41–48 | FastAPI、数据库、Web、Docker、安全、部署 | 完整 AI 毕业项目 |

详细的逐周任务、项目和验收标准见 [48 周学习路线](roadmap/36-week-roadmap.md)。

## 项目驱动方法

每个阶段都遵循同一过程：

1. 选定一个真实问题和最小可用目标；
2. 拆解需求、数据流和技术任务；
3. 学一个概念，立即在项目里实践；
4. 自己编写关键部分，让 Codex 提示和审查；
5. 运行测试，记录结果和失败案例；
6. 写清楚如何安装、运行和复现；
7. 完成阶段验收后再进入下一阶段。

## 每日 2 小时节奏

- 10 分钟：回顾上次学习和问题；
- 25 分钟：阅读教材或官方文档；
- 65 分钟：项目实践、编码和调试；
- 15 分钟：笔记、测试结果和学习记录；
- 5 分钟：写下下次的第一个动作。

## 仓库目录

- `AGENTS.md`：Codex 长期教学和工程协作规则
- `roadmap/`：阶段路线、逐周任务和验收标准
- `daily-logs/`：每日学习记录
- `notes/`：知识点、术语和问题笔记
- `projects/`：阶段项目和毕业项目
- `resources/`：精选教材、文档和开源项目

## 当前主教材与资源

- [Python-100-Days](https://github.com/jackfrued/Python-100-Days)
- [动手学深度学习（中文）](https://zh.d2l.ai/)
- [南瓜书](https://github.com/datawhalechina/pumpkin-book)
- [Happy-LLM](https://github.com/datawhalechina/happy-llm)
- [LLM Universe](https://github.com/datawhalechina/llm-universe)
- [Hello-Agents](https://github.com/datawhalechina/hello-agents)
- [All-in-RAG](https://github.com/datawhalechina/all-in-rag)
- [MCP 官方文档](https://modelcontextprotocol.io/docs/getting-started/intro)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)

按当前阶段选择主教材，不需要一次性下载或学习所有仓库。优先在线阅读；只有需要运行源码时才下载对应示例或项目。

## MacBook 与 Windows 同步约定

- 两台设备分别克隆同一个仓库。
- 每台设备独立创建自己的 Python 虚拟环境。
- 切换设备前先检查工作区并同步远程更新。
- 不提交 `.venv/`、`.env`、API Key、密码、模型权重和大型数据集。
- 避免两台设备同时修改同一个文件。
- Git 提交和推送前先检查变更内容。

## 当前准备进度

- [x] 创建 GitHub 学习仓库
- [x] MacBook 安装并识别 Git
- [x] 本地仓库关联远程 origin
- [x] 验证能够读取远程 main 分支
- [x] 建立第一版 AGENTS.md（本次升级为长期规则）
- [ ] 将更新后的 README、路线和 AGENTS 同步到 MacBook
- [ ] 检查 Python 虚拟环境
- [ ] 完成 Codex 项目读取测试
- [ ] 完成 Day 0 环境验收
- [ ] 开始 Day 1：Python 基础与第一个小项目

## 下一步

完成 Day 0 环境验收后，从路线第 1 周开始。第一项实战是制作一个命令行学习助手，逐步加入文件保存、API 调用和测试。
