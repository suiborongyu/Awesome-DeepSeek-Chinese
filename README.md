# 🚀 Awesome DeepSeek R1 Chinese Guide (深度求索应用指南)

> **一句话介绍：**
> 拒绝昂贵的订阅费，告别官网卡顿。这里汇集了 DeepSeek R1 **满血版本地部署**、**企业级工作流 (Dify/RAG)** 以及 **能落地的行业变现** 方案，帮你零成本构建最强 AI 大脑。

<p align="center">
  <a href="#-加入私域流量池-获取一手情报">
    <img src="https://img.shields.io/badge/点击加入-DeepSeek实战交流群-blue?style=for-the-badge&logo=wechat" alt="加入交流群">
  </a>
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO_NAME?style=for-the-badge" alt="Stars">
  <img src="https://img.shields.io/github/last-commit/YOUR_USERNAME/YOUR_REPO_NAME?style=for-the-badge" alt="Last Commit">
</p>

---

## 📖 目录 (Table of Contents)

- [🔥 必读：为什么选择 DeepSeek R1？](#-必读为什么选择-deepseek-r1)
- [🚨 新手入门：官网崩了怎么办？](#-新手入门官网崩了怎么办)
- [💻 进阶部署：本地满血版教程 (Ollama/vLLM)](#-进阶部署本地满血版教程)
- [⚡ 生产力流派：DeepSeek + Dify / AnythingLLM](#-生产力流派工作流与rag)
- [🧠 行业提示词库：绝密 Prompt 清单](#-行业提示词库)
- [🧰 核心工具箱：10 大开源神器](#-核心工具箱10-大开源神器)
- [💰 变现与案例：普通人如何用它搞钱](#-变现与案例)
- [🤝 贡献与交流](#-贡献与交流)

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

## 🚨 新手入门：官网崩了怎么办？
*当 `deepseek.com` 显示 "服务器繁忙" 时，即使没有显卡，你也可以用这些方案：*

- **硅基流动 (SiliconFlow):** 注册即送额度，满血版 API 调用教程。
- **秘塔 AI / 纳米搜索:** 内置 DeepSeek 引擎的平替工具。
- **手机端方案:** 即使是安卓/iOS 也能跑通的轻量级 App 推荐。

## 💻 进阶部署：本地满血版教程
*数据隐私？断网运行？看这里：*

- **Ollama 一键部署:** `ollama run deepseek-r1:7b` (及如何解决显存不足报错)。
- **Page Assist 插件:** 让本地模型像 Chrome 插件一样随叫随到。
- **知识库搭建:** 配合 MaxKB 或 AnythingLLM 喂给它你所有的 PDF 文档。

## 🧠 行业提示词库
*经过 1000+ 次测试的 DeepSeek 专用“深度思考”指令：*

| 场景 | 简介 | 链接 |
| :--- | :--- | :--- |
| **学术/学生** | 论文润色、降重、文献综述自动生成 | [查看 Prompt](./prompts/academic.md) |
| **自媒体** | 小红书爆款标题、口语化文案重写 | [查看 Prompt](./prompts/social-media.md) |
| **程序员** | 代码审计、LeetCode 解题思路、Bug 修复 | [查看 Prompt](./prompts/coding.md) |
| **求职者** | 简历优化、模拟面试官 (压力面试) | [查看 Prompt](./prompts/interview.md) |

---

## 🧰 核心工具箱：10 大开源神器

以下项目完美适配 DeepSeek，建议 Star 收藏：

| 项目名称 | 核心功能 | 推荐理由 |
| :--- | :--- | :--- |
| **[Ollama](https://github.com/ollama/ollama)** | 模型运行器 | 本地部署 DeepSeek 的基石，命令行神器。 |
| **[Cherry Studio](https://github.com/cherry-ai/cherry-studio)** | 桌面客户端 | 高颜值、支持多模型切换，体验极佳的 GUI。 |
| **[Dify](https://github.com/langgenius/dify)** | LLM 应用开发 | **最强推荐**，零代码搭建 Agent 和工作流。 |
| **[MaxKB](https://github.com/1Panel-dev/MaxKB)** | 知识库问答 | 基于 LLM 的企业级知识库，RAG 效果好，适合内网。 |
| **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)** | 私人文档库 | 隐私性极强，支持全格式文档投喂。 |
| **[Chatbox](https://github.com/Bin-Huang/chatbox)** | 多平台客户端 | 开源老牌客户端，支持 API 转发，稳定。 |
| **[Lobe Chat](https://github.com/lobehub/lobe-chat)** | 现代化 UI | 界面极其华丽，插件生态丰富（画图/联网）。 |
| **[Page Assist](https://github.com/nathan-149/page-assist)** | 浏览器侧边栏 | 能够读取当前网页内容并让 DeepSeek 总结。 |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | 仿 ChatGPT | 功能最全的 Web 界面，支持语音、图像等多模态。 |
| **[Cline](https://github.com/cline/cline)** | 编程助手 | VS Code 里的最强 AI 助手，配合 DeepSeek 编程成本极低。 |

---

## 💰 变现与案例 (Coming Soon)
- [ ] 如何用 DeepSeek 批量生成儿童绘本故事 (闲鱼变现)
- [ ] 搭建垂直领域法律顾问 AI (企业服务)
- [ ] 自动化生成 SEO 垃圾站内容 (流量主)

---
