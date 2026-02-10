# 🚀 Awesome DeepSeek R1 Chinese Guide (深度求索应用指南)

> **一句话介绍：**
> 拒绝昂贵的订阅费，告别官网卡顿。这里汇集了 DeepSeek R1 **满血版本地部署**、**企业级工作流 (Dify/RAG)** 以及 **能落地的行业变现** 方案，帮你零成本构建最强 AI 大脑。
>
> **🔥 新增：** **[Dify 实战工作流库（闲鱼同款高转化工作流，一键导入）](#-dify-实战工作流库)**——直接复用作者在闲鱼实战用的 Dify 工作流，少踩 90% 的坑。

<p align="center">
  <a href="#-加入私域流量池-获取一手情报">
    <img src="https://img.shields.io/badge/点击加入-DeepSeek实战交流群-blue?style=for-the-badge&logo=wechat" alt="加入交流群">
  </a>
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO_NAME?style=for-the-badge" alt="Stars">
  <img src="https://img.shields.io/github/last-commit/YOUR_USERNAME/YOUR_REPO_NAME?style=for-the-badge" alt="Last Commit">
</p>

---

## ⚡ 快速路径 (Quick Navigation)

> **🎯 新手必看：** 不知道从哪里开始？直接点击下方链接，3分钟上手！

| 📄 文档 | 🎯 适合人群 | 📝 核心内容 |
| :--- | :--- | :--- |
| **[🚀 3分钟极速启动](./Quick_Start.md)** | 所有人 | 本地部署 + 云端平替，立即用上 DeepSeek R1 |
| **[🧠 提示词库大全](./Prompts_Library.md)** | 学生/职场/程序员/自媒体 | 4类人群专家级指令 + 调优技巧 |
| **[💰 变现实战指南](./Monetization.md)** | 想搞钱的你 | 3个低门槛案例 + 立即行动清单 |
| **[🛠️ 工具下载中心](./Tools_Download.md)** | 需要工具的开发者 | 所有客户端/插件/手机端方案下载链接 |
| **[⚙️ Dify 实战工作流库](#-dify-实战工作流库)** | Dify 用户 / 工作流搭建者 | 闲鱼同款高转化工作流索引 + 导入教程 |

---

## 📖 目录 (Table of Contents)

- [⚡ 快速路径 (Quick Navigation)](#-快速路径-quick-navigation)
- [🔥 必读：为什么选择 DeepSeek R1？](#-必读为什么选择-deepseek-r1)
- [🚀 3分钟极速启动 (Quick Start)](#-3分钟极速启动-quick-start)
- [🚨 新手入门：官网崩了怎么办？](#-新手入门官网崩了怎么办)
- [💻 进阶部署：本地满血版教程 (Ollama/vLLM)](#-进阶部署本地满血版教程)
- [⚡ 生产力流派：DeepSeek + Dify / AnythingLLM](#-生产力流派工作流与rag)
- [⚙️ Dify 实战工作流库（含闲鱼工作流）](#-dify-实战工作流库)
- [🧠 行业提示词库：绝密 Prompt 清单](#-行业提示词库)
- [🧰 核心工具箱：10 大开源神器](#-核心工具箱10-大开源神器)
- [💰 变现与案例：普通人如何用它搞钱](#-变现与案例)
- [🤝 联系作者 / 领取完整资源包](#-联系作者--领取完整资源包)

---

## 🎁 加入私域流量池 获取一手情报

**GitHub 仓库更新较慢，想获取最新的：**
1.  **DeepSeek 满血版模型网盘下载链接** (防止 HuggingFace 被墙)
2.  **企业级 Dify 自动化工作流 JSON 模板** (直接导入可用)
3.  **每日更新的“搞钱”实战案例拆解**

👇 **请扫描下方二维码 / 关注公众号 [您的公众号名称] 回复 "DeepSeek" 立即获取：**

> ![占位符：此处放置您的二维码图片](https://via.placeholder.com/150x150?text=QR+Code)
> 
> *已有 500+ 开发者与自媒体人加入，进群不迷路。*

---

## 🚀 3分钟极速启动 (Quick Start)

> **🎯 核心目标：** 无论官网是否崩了，你都能通过以下两种方式（本地部署 / 云端平替）立即用上 DeepSeek R1。

👉 **[📖 查看完整快速启动指南](./Quick_Start.md)** - 包含详细的安装步骤、模型选择建议和常见问题排查。

**快速预览：**
- **本地部署（永久免费）：** 使用 Ollama 一键安装，根据内存选择对应模型版本（1.5b / 7b / 14b）
- **云端平替（免显卡）：** 硅基流动、HuggingFace Chat、秘塔 AI 等镜像站推荐

---

## 🚨 新手入门：官网崩了怎么办？
*当 `deepseek.com` 显示 "服务器繁忙" 时，即使没有显卡，你也可以用这些方案：*

> 💡 **推荐先看：** [🚀 3分钟极速启动指南](./Quick_Start.md) - 包含完整的本地部署和云端替代方案

- **硅基流动 (SiliconFlow):** 注册即送额度，满血版 API 调用教程。
- **秘塔 AI / 纳米搜索:** 内置 DeepSeek 引擎的平替工具。
- **手机端方案:** 即使是安卓/iOS 也能跑通的轻量级 App 推荐。

## 💻 进阶部署：本地满血版教程
*数据隐私？断网运行？看这里：*

- **Ollama 一键部署:** `ollama run deepseek-r1:7b` (及如何解决显存不足报错)。
- **Page Assist 插件:** 让本地模型像 Chrome 插件一样随叫随到。
- **知识库搭建:** 配合 MaxKB 或 AnythingLLM 喂给它你所有的 PDF 文档。

---

## ⚙️ Dify 实战工作流库

> **📂 所有模板位置：** `闲鱼dify工作流/可参考的dify工作流模板/` 目录下，文件名 = 功能场景。
>
> **📘 使用教程：** 强烈建议先阅读 **[《Dify 实战工作流库使用说明》](./Dify_Usage.md)**，手把手教你导入这些 `.yml` 到自己的 Dify 环境。

这些工作流大部分来自作者在 **闲鱼真实项目** 中使用的模板，覆盖了发票识别、股票分析、自媒体创作、知识库检索、AI 绘画等高频场景。

### 🔍 核心示例工作流一览（更多请直接查看目录）

> 下表列出了常用、高需求的代表性工作流，方便你快速找到适合自己的模板。  
> **提示：** 其余未列出但同样可用的模板，可直接在对应目录中按文件名选择。

| 工作流文件名 | 功能场景（根据文件名推断） |
| :--- | :--- |
| `SQL 生成器.yml` | 根据自然语言自动生成 SQL 查询语句，适合 BI / 数据分析 |
| `学生成绩查询工作流（带数据库查询）.yml` | 通过数据库查询学生成绩的教务查询工作流 |
| `自然语言查询PG数据库.yml` | 面向 PostgreSQL 的自然语言数据查询助手 |
| `知识库检索工作流.yml` | 基于知识库的问答 / RAG 检索工作流基础模板 |
| `解析网页内容存到知识库.yml` | 抓取网页内容并写入 Dify 知识库，支持后续问答 |
| `图文知识库.yml` | 图文混合知识库构建与检索示例 |
| `深度seek 文档翻译器.yml` | 针对文档的 DeepSeek 翻译工作流（长文翻译） |
| `DeepSeek-R1（永不掉线）.yml` | 深度优化的 DeepSeek-R1 调用工作流，稳定长时间运行 |
| `Dify 运营一条龙.yml` | 从内容生成到发布的一体化 Dify 运营工作流 |
| `dify_course_demo.yml` | Dify 官方/教学演示用课程 Demo 工作流 |
| `文献综述写作.yml` | 自动生成/辅助撰写学术文献综述 |
| `文本总结工作流.yml` | 长文本/会议记录自动总结 |
| `儿童故事绘本工作流.yml` | 自动生成儿童故事 + 绘本结构 |
| `儿童故事绘本文生视频语音合成版 .yml` | 儿童故事 → 视频 + 语音播报的整合工作流 |
| `儿童故事绘本-PPT chatflow.yml` | 生成儿童故事 PPT 的 Chatflow 工作流 |
| `儿童故事绘本-PPT Agent.yml` | 以 Agent 形式生成儿童故事 PPT |
| `小红书文案生成器.yml` | 专门面向小红书风格的爆款文案生成 |
| `SEO 文章生成专家.yml` | 针对 SEO 场景的长文内容生成 |
| `SEO 博客生成工作流.yml` | 博客类 SEO 文章的结构化生成工作流 |
| `YouTube博主和自媒体运营专家工作流.yml` | 面向 YouTube / 自媒体运营的内容策划与脚本生成 |
| `AI资讯每日新闻+语音播报工作流.yml` | 每日 AI 资讯抓取 + 文案生成 + 语音播报 |
| `股票分析系统.yml` | 通用股票分析助手，支持财务/技术指标解读 |
| `股票分析系统-Gordon修改版.yml` | 经过 Gordon 优化的股票分析系统增强版 |
| `股票分析AI小助理.yml` | 轻量级股票分析问答助手 |
| `抓股票最近30工作日kdj.yml` | 抓取并分析最近 30 日 KDJ 指标 |
| `抓股票最近30工作日macd.yml` | 抓取并分析最近 30 日 MACD 指标 |
| `抓股票最近30工作日成交数据.yml` | 抓取最近 30 日成交量/价格数据 |
| `大模型表格解析自动生成代码生成统计图.yml` | 读取表格 → 自动生成代码 → 输出统计图 |
| `Excel解析生成图表.yml` | 解析 Excel 并生成可视化图表 |
| `excel表格提取+echarts展示.yml` | 从 Excel 中抽取数据并用 ECharts 展示 |
| `增值税发票提取小工具chatflow.yml` | 增值税发票关键信息提取 Chatflow 工作流 |
| `发票提取小工具整合版-变量聚合器.yml` | 发票信息提取整合版，支持复杂变量聚合 |
| `发票比对专家-新版客运火车票2.yml` | 针对火车票等票据的发票信息比对专家 |
| `电费单识别.yml` | 电费账单 OCR + 结构化提取 |
| `门诊导诊.yml` | 医疗门诊导诊问答 / 分诊助手 |
| `法律文本格式化助手.yml` | 法律条文/合同格式化与排版优化 |
| `合同审查.yml` | 合同条款风险点识别与审查建议 |
| `客户评价处理工作流.yml` | 自动提取和分析客户评价情感/主题 |
| `智能客服助手.yml` | 通用智能客服工作流，可接入网站/小程序 |
| `文润 · 妙笔生花.yml` | 面向写作润色的“妙笔生花”文案助手 |
| `长文写作.yml` | 大纲驱动的长文写作助手 |
| `个人学习导师.yml` | 结合用户输入的个性化学习计划/辅导导师 |
| `旅行规划助手.yml` | 根据目的地和偏好自动生成旅行计划 |
| `旅行Demo.yml` | 旅行场景 Demo 工作流，适合二次改造 |
| `gemini-2.0-flash-exp-image-generation-文生图智能体.yml` | 基于 Gemini 的文生图智能体示例 |
| `即梦AI绘画.yml` | 即梦类 AI 绘画工作流 |
| `即梦AI绘画-飞书表格+企业微信.yml` | AI 绘画 + 飞书表格 + 企业微信联动 |
| `FLUX绘画机器人.yml` | 基于 FLUX 的绘画机器人工作流 |
| `FLUX绘画机器人+多模态识别+语音播放.yml` | 绘画 + 多模态识别 + 语音播放一体化工作流 |
| `赛博朋克插画生成.yml` | 赛博朋克风格插画生成器 |
| `扁平风插画生成.yml` | 扁平化插画/ICON 风格生成 |
| `SVG Logo 设计.yml` | SVG Logo 自动设计与生成 |
| `春联生成器.yml` | 通用春联文案生成器 |
| `春联生成器 (“福”到了版本).yml` | 带“福到”创意的春联生成器 |
| `标题党创作.yml` | 标题党文案/钩子标题自动生成 |
| `科普文章作者（嵌套并行）.yml` | 支持嵌套并行推理的科普文章写作 |
| `ChatPaper.yml` | 论文阅读与总结助手 ChatPaper 工作流版 |
| `Deep Researcher On Dify .yml` | 多步深度检索 + 总结的研究型工作流 |
| `GPT-Researcher .yml` | GPT-Researcher 风格的深度研究助手 |
| `DeepResearch.yml` | 通用多轮深度调研工作流 |
| `help me think(deepseek r1).yml` | 基于 DeepSeek R1 的“帮我思考”工作流 |
| `推理模型选择是否输出思考内容.yml` | 控制推理模型是否展示思维链的实验性工作流 |
| `思考助手.yml` | 面向复杂问题拆解的思考助手 |
| `思考式 Claude (OpenAI O1代替品).yml` | 模拟 Claude/O1 风格的思考式回答 |
| `ModelPK.yml` | 多模型对比 PK 工作流 |
| `模型竞技场（简单并行）.yml` | 简单并行结构的模型竞技场 |
| `思维导图生成助手.yml` | 从文本生成思维导图结构 |
| `思维导图生成助手mindmap_generator.yml` | mindmap_generator 版本的思维导图助手 |
| `数据统计分析.yml` | 通用数据统计与可视化分析助手 |
| `互联网搜索与分析.yml` | 联网搜索 + 结果分析一体化 |
| `联网搜索.yml` | 轻量级联网搜索调用工作流 |
| `NotebookLM.yml` | NotebookLM 风格的文档理解助手 |
| `NotebookLM by Dify.AI.yml` | Dify 定制版 NotebookLM 工作流 |
| `AI 前端面试官.yml` | 模拟前端工程师面试官，进行问答与评分 |
| `ai agent智能体.yml` | 通用 AI Agent 智能体工作流 |
| `Agent工具调用.yml` | 展示 Agent + 工具调用模式的示例 |
| `API文档生成代码.yml` | 根据 API 文档自动生成调用代码 |
| `Python Coding Prompt.yml` | 辅助 Python 编码与调试的工作流 |
| `runLLMCode.yml` | 执行 LLM 生成代码的工作流模板 |
| `MCP.yml` | 结合 MCP（Model Context Protocol）的工作流示例 |
| `json-repair.yml` | 自动修复非标准 JSON 字符串 |
| `json_translate.yml` | 针对 JSON 结构文本的翻译助手 |
| `LanguageConsistencyChecker.yml` | 多语言内容一致性检查工具 |
| `jieba.yml` | 基于 jieba 的中文分词/预处理工作流 |
| `Jina Reader Jinja.yml` | 基于 Jina Reader 的网页内容读取 + 渲染 |

> ✅ **提示：** 如果你是进阶用户，建议直接结合这些模板和 `Dify_Usage.md` 中的 RAG 调优建议，按需二次改造。

## 🧠 行业提示词库

> 💡 **完整提示词库：** 查看 [🧠 提示词库大全](./Prompts_Library.md) 获取 4 类人群的专家级指令和调优技巧

*经过 1000+ 次测试的 DeepSeek 专用"深度思考"指令：*

| 场景 | 简介 | 链接 |
| :--- | :--- | :--- |
| **🎓 学生/学术** | 论文润色、降重、文献综述自动生成 | [查看指令](./Prompts_Library.md#-学生学术场景) |
| **💼 职场/求职** | 简历优化、模拟面试官、压力面试训练 | [查看指令](./Prompts_Library.md#-职场求职场景) |
| **💻 程序员/开发** | 代码审计、LeetCode 解题、Bug 修复 | [查看指令](./Prompts_Library.md#-程序员开发场景) |
| **📱 自媒体/内容** | 小红书爆款标题、口语化文案重写 | [查看指令](./Prompts_Library.md#-自媒体内容创作) |

---

## 🧰 核心工具箱：10 大开源神器

> 💡 **完整下载链接：** 查看 [🛠️ 工具下载中心](./Tools_Download.md) 获取所有工具的安装包和详细说明

以下项目完美适配 DeepSeek，建议 Star 收藏：

| 🛠️ 工具 | 📦 类型 | ⭐ 必用理由 |
| :--- | :--- | :--- |
| **[Ollama](https://github.com/ollama/ollama)** | 模型运行器 | **本地部署基石** - 一条命令启动 DeepSeek，无需配置环境变量 |
| **[Cherry Studio](https://github.com/cherry-ai/cherry-studio)** | 桌面客户端 | **颜值天花板** - 支持多模型无缝切换，界面比 ChatGPT 还好看 |
| **[Dify](https://github.com/langgenius/dify)** | LLM 应用开发 | **零代码神器** - 拖拽式搭建 AI Agent，企业级工作流 5 分钟搞定 |
| **[MaxKB](https://github.com/1Panel-dev/MaxKB)** | 知识库问答 | **内网首选** - RAG 效果吊打 LangChain，支持私有化部署 |
| **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)** | 私人文档库 | **隐私之王** - 全格式文档投喂，数据永不外传，适合敏感行业 |
| **[Chatbox](https://github.com/Bin-Huang/chatbox)** | 多平台客户端 | **稳定老将** - 开源 3 年+，支持 API 转发，团队协作首选 |
| **[Lobe Chat](https://github.com/lobehub/lobe-chat)** | 现代化 UI | **插件生态** - 内置画图/联网/语音，一个界面搞定所有 AI 需求 |
| **[Page Assist](https://github.com/nathan-149/page-assist)** | 浏览器插件 | **网页助手** - 自动读取当前页面，让 DeepSeek 帮你总结/翻译 |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | Web 界面 | **功能最全** - 支持语音输入、图像识别，多模态体验拉满 |
| **[Cline](https://github.com/cline/cline)** | VS Code 插件 | **编程神器** - VS Code 里最强 AI 助手，写代码效率提升 10 倍 |

---

## 💰 变现与案例

> 💡 **完整变现指南：** 查看 [💰 变现实战指南](./Monetization.md) 获取 3 个低门槛案例和立即行动清单

**快速预览：**
- 🎨 **代部署服务** - 帮小白安装 Ollama，一次收费 50-200 元
- 📚 **垂直知识库搭建** - 为企业搭建法律/医疗 AI 顾问，月入 5000+
- ✍️ **AI 内容代运营** - 批量生成小红书/公众号内容，按篇收费

---

## 🤝 联系作者 / 领取完整资源包

> **🎁 限时福利：** 关注公众号或添加微信，立即领取以下资源（价值 500+ 元）

### 📦 资源包内容

1. **📥 DeepSeek 模型网盘下载链接** (防止 HuggingFace 被墙，下载速度提升 10 倍)
2. **📋 企业级 Dify 工作流 JSON 模板** (直接导入可用，包含 10+ 行业场景)
3. **💼 每日更新的"搞钱"实战案例拆解** (闲鱼/小红书/企业服务全流程)
4. **🎯 100+ 精选 Prompt 指令库** (学生/职场/程序员/自媒体全覆盖)
5. **🛠️ 所有工具的国内镜像下载地址** (解决 GitHub 访问慢的问题)

### 🔗 获取方式

**方式一：微信扫码（推荐）**
> ![微信二维码](https://via.placeholder.com/200x200?text=WeChat+QR+Code)
> 
> *扫码后回复 "DeepSeek" 自动获取资源包*

**方式二：闲鱼搜索**
> 搜索关键词：**"DeepSeek 部署"** 或 **"AI 模型安装"**
> 
> 找到作者店铺，下单后立即发货（包含视频教程 + 一对一答疑）

**方式三：GitHub Issue**
> 在仓库 [Issues](https://github.com/suiborongyu/Awesome-DeepSeek-Chinese/issues) 中留言，作者会定期回复

---

> **💬 已有 500+ 开发者与自媒体人加入，进群不迷路。**
> 
> *所有资源包永久更新，一次获取，终身受益！*

---
