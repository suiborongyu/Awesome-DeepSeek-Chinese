# 🛠️ DeepSeek R1 工具下载中心

> **一站式资源聚合：** 所有 DeepSeek 相关的客户端、插件、手机端方案，这里全都有。

---

## 📚 目录

- [💻 桌面客户端](#-桌面客户端)
- [🌐 浏览器插件](#-浏览器插件)
- [📱 手机端方案](#-手机端方案)
- [🔧 开发工具](#-开发工具)
- [📦 国内镜像下载](#-国内镜像下载)

---

## 💻 桌面客户端

### 1. Ollama（模型运行器）

**🎯 必用理由：** 本地部署 DeepSeek 的基石，一条命令启动，无需配置环境变量。

| 平台 | 下载链接 | 安装说明 |
| :--- | :--- | :--- |
| **Windows** | [官方下载](https://ollama.com/download/windows) | 下载 `.exe` 安装包，一路"下一步"即可 |
| **macOS** | [官方下载](https://ollama.com/download/mac) | 下载 `.dmg` 文件，拖拽到 Applications |
| **Linux** | [官方下载](https://ollama.com/download/linux) | 运行：`curl -fsSL https://ollama.com/install.sh \| sh` |

**🚀 快速启动：**
```bash
# 安装完成后，打开终端运行：
ollama run deepseek-r1:7b
```

**💡 避坑提示：**
- 如果下载慢，可以使用 [国内镜像](#-国内镜像下载)
- 首次运行会自动下载模型（约 4-10GB），请耐心等待
- 如果报错 "out of memory"，请选择更小的模型版本（如 1.5b）

---

### 2. Cherry Studio（高颜值桌面客户端）

**🎯 必用理由：** 界面比 ChatGPT 还好看，支持多模型无缝切换，体验极佳。

| 平台 | 下载链接 | 安装说明 |
| :--- | :--- | :--- |
| **Windows** | [GitHub Releases](https://github.com/cherry-ai/cherry-studio/releases) | 下载 `Cherry-Studio-Setup-x.x.x.exe` |
| **macOS** | [GitHub Releases](https://github.com/cherry-ai/cherry-studio/releases) | 下载 `Cherry-Studio-x.x.x.dmg` |
| **Linux** | [GitHub Releases](https://github.com/cherry-ai/cherry-studio/releases) | 下载 `.AppImage` 文件，添加执行权限后运行 |

**🔗 项目地址：** [https://github.com/cherry-ai/cherry-studio](https://github.com/cherry-ai/cherry-studio)

**💡 使用提示：**
- 首次使用需要配置 Ollama 连接（默认地址：`http://localhost:11434`）
- 支持同时连接多个模型，可以快速切换对比效果

---

### 3. Chatbox（开源老牌客户端）

**🎯 必用理由：** 开源 3 年+，稳定性极强，支持 API 转发，团队协作首选。

| 平台 | 下载链接 | 安装说明 |
| :--- | :--- | :--- |
| **Windows** | [GitHub Releases](https://github.com/Bin-Huang/chatbox/releases) | 下载 `Chatbox-x.x.x-win.exe` |
| **macOS** | [GitHub Releases](https://github.com/Bin-Huang/chatbox/releases) | 下载 `Chatbox-x.x.x-mac.dmg` |
| **Linux** | [GitHub Releases](https://github.com/Bin-Huang/chatbox/releases) | 下载 `.AppImage` 文件 |

**🔗 项目地址：** [https://github.com/Bin-Huang/chatbox](https://github.com/Bin-Huang/chatbox)

**💡 特色功能：**
- 支持自定义 API 端点（可以转发到其他服务）
- 支持导出对话记录（JSON/Markdown 格式）
- 支持多窗口同时使用

---

### 4. Lobe Chat（现代化 UI）

**🎯 必用理由：** 界面极其华丽，插件生态丰富（画图/联网/语音），一个界面搞定所有 AI 需求。

| 安装方式 | 说明 |
| :--- | :--- |
| **Docker** | `docker run -d -p 3210:3210 lobehub/lobe-chat` |
| **npm** | `npm install -g lobe-chat && lobe-chat` |
| **源码编译** | [查看文档](https://github.com/lobehub/lobe-chat) |

**🔗 项目地址：** [https://github.com/lobehub/lobe-chat](https://github.com/lobehub/lobe-chat)

**💡 使用提示：**
- 推荐使用 Docker 方式安装，最简单
- 首次访问：`http://localhost:3210`
- 支持插件市场，可以安装画图、联网等插件

---

## 🌐 浏览器插件

### 1. Page Assist（网页助手）

**🎯 必用理由：** 自动读取当前网页内容，让 DeepSeek 帮你总结/翻译/改写，随叫随到。

| 浏览器 | 下载链接 |
| :--- | :--- |
| **Chrome** | [Chrome Web Store](https://chrome.google.com/webstore/detail/page-assist/...) |
| **Edge** | [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/...) |
| **Firefox** | [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/...) |

**🔗 项目地址：** [https://github.com/nathan-149/page-assist](https://github.com/nathan-149/page-assist)

**💡 使用场景：**
- 阅读长文章时，一键总结核心观点
- 浏览外文网站时，实时翻译并解释
- 写论文时，快速提取参考文献的关键信息

---

### 2. Cline（VS Code 编程助手）

**🎯 必用理由：** VS Code 里最强 AI 助手，写代码效率提升 10 倍，配合 DeepSeek 编程成本极低。

| 安装方式 | 说明 |
| :--- | :--- |
| **VS Code 扩展** | 在 VS Code 中搜索 "Cline" 并安装 |
| **手动安装** | [查看文档](https://github.com/cline/cline) |

**🔗 项目地址：** [https://github.com/cline/cline](https://github.com/cline/cline)

**💡 使用提示：**
- 安装后需要在设置中配置 API 端点（Ollama 地址：`http://localhost:11434`）
- 支持代码补全、代码解释、Bug 修复等多种功能
- 快捷键：`Ctrl + L` 打开对话窗口

---

## 📱 手机端方案

### 1. Open WebUI（移动端访问）

**🎯 必用理由：** 在电脑上部署 Open WebUI，手机浏览器直接访问，无需安装 App。

**📋 部署步骤：**

1. **在电脑上安装 Docker**
   ```bash
   # Windows/Mac: 下载 Docker Desktop
   # Linux: sudo apt install docker.io
   ```

2. **运行 Open WebUI**
   ```bash
   docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
   ```

3. **手机访问**
   - 确保手机和电脑在同一 WiFi 网络
   - 在手机浏览器输入：`http://[电脑IP]:3000`
   - 例如：`http://192.168.1.100:3000`

**🔗 项目地址：** [https://github.com/open-webui/open-webui](https://github.com/open-webui/open-webui)

---

### 2. API 转发 + 第三方客户端

**🎯 必用理由：** 如果不想在电脑上部署，可以使用 API 转发服务，手机 App 直接连接。

**📋 推荐 App：**

| App 名称 | 平台 | 下载链接 | 说明 |
| :--- | :--- | :--- | :--- |
| **ChatGPT API** | iOS | [App Store](https://apps.apple.com/app/chatgpt-api/id...) | 支持自定义 API 端点 |
| **AI Chat** | Android | [Google Play](https://play.google.com/store/apps/details?id=...) | 开源免费，支持 Ollama |
| **Poe** | iOS/Android | [官网](https://poe.com/) | 支持多种模型，需要 API Key |

**💡 配置步骤：**
1. 在电脑上运行 Ollama（确保允许外部访问）
2. 配置 API 转发（可以使用 Nginx 或 Caddy）
3. 在手机 App 中填入 API 地址和密钥

---

## 🔧 开发工具

### 1. Dify（LLM 应用开发平台）

**🎯 必用理由：** 零代码搭建 AI Agent，企业级工作流 5 分钟搞定，最强推荐。

| 安装方式 | 说明 |
| :--- | :--- |
| **Docker Compose** | [查看文档](https://docs.dify.ai/getting-started/install-self-hosted) |
| **一键脚本** | `curl -fsSL https://get.dify.ai | bash` |

**🔗 项目地址：** [https://github.com/langgenius/dify](https://github.com/langgenius/dify)

**💡 使用提示：**
- 推荐使用 Docker Compose 方式，最简单
- 首次访问：`http://localhost/v2`（默认账号：admin@dify.ai，密码：difyai123456）
- 支持导入工作流模板，快速搭建应用

---

### 2. MaxKB（知识库问答系统）

**🎯 必用理由：** 基于 LLM 的企业级知识库，RAG 效果好，适合内网部署。

| 安装方式 | 说明 |
| :--- | :--- |
| **Docker** | `docker run -d -p 8080:8080 maxkb/maxkb` |
| **源码编译** | [查看文档](https://github.com/1Panel-dev/MaxKB) |

**🔗 项目地址：** [https://github.com/1Panel-dev/MaxKB](https://github.com/1Panel-dev/MaxKB)

**💡 使用提示：**
- 首次访问：`http://localhost:8080`
- 支持多种文档格式：PDF、Word、Excel、Markdown
- 可以配置 DeepSeek R1 作为 LLM 引擎

---

### 3. AnythingLLM（私人文档库）

**🎯 必用理由：** 隐私性极强，全格式文档投喂，数据永不外传，适合敏感行业。

| 安装方式 | 说明 |
| :--- | :--- |
| **Docker** | `docker run -d -p 3001:3001 -v anythingllm_data:/app/server/storage anythingllm/anythingllm` |
| **桌面版** | [下载安装包](https://github.com/Mintplex-Labs/anything-llm/releases) |

**🔗 项目地址：** [https://github.com/Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)

**💡 使用提示：**
- 首次访问：`http://localhost:3001`
- 支持本地部署，数据完全私有
- 可以连接 Ollama 使用 DeepSeek R1

---

## 📦 国内镜像下载

> **💡 提示：** 如果 GitHub 或官方下载源速度慢，可以使用以下国内镜像。

### Ollama 模型镜像

| 镜像源 | 地址 | 说明 |
| :--- | :--- | :--- |
| **阿里云镜像** | [配置方法](https://mirrors.aliyun.com/ollama/) | 需要手动配置镜像地址 |
| **清华大学镜像** | [配置方法](https://mirrors.tuna.tsinghua.edu.cn/ollama/) | 教育网用户推荐 |
| **网盘下载** | [百度网盘/阿里云盘](链接待补充) | 直接下载模型文件（GGUF 格式） |

**🔧 配置方法：**
```bash
# 设置环境变量（Linux/Mac）
export OLLAMA_HOST=https://mirrors.aliyun.com/ollama

# Windows PowerShell
$env:OLLAMA_HOST="https://mirrors.aliyun.com/ollama"
```

---

### GitHub 加速

| 工具 | 说明 | 下载链接 |
| :--- | :--- | :--- |
| **GitHub 加速器** | 浏览器插件，自动加速 GitHub 下载 | [Chrome 扩展](https://chrome.google.com/webstore/detail/github-accelerator/...) |
| **FastGit** | 替换 GitHub 链接为国内镜像 | [官网](https://hub.fastgit.xyz/) |
| **GitClone** | 一键克隆 GitHub 仓库 | [官网](https://gitclone.com/) |

---

### Docker 镜像加速

**配置 Docker 镜像源（国内用户必做）：**

1. **编辑 Docker 配置文件**
   ```bash
   # Linux: /etc/docker/daemon.json
   # Windows/Mac: Docker Desktop -> Settings -> Docker Engine
   ```

2. **添加镜像源**
   ```json
   {
     "registry-mirrors": [
       "https://docker.mirrors.ustc.edu.cn",
       "https://hub-mirror.c.163.com"
     ]
   }
   ```

3. **重启 Docker**
   ```bash
   # Linux
   sudo systemctl restart docker
   
   # Windows/Mac: 重启 Docker Desktop
   ```

---

## 📖 更多资源

- [返回 README](./README.md)
- [查看快速启动指南](./Quick_Start.md)
- [查看提示词库](./Prompts_Library.md)
- [查看变现实战指南](./Monetization.md)

---

> **💡 提示：** 如果遇到下载问题，可以在仓库 [Issues](https://github.com/suiborongyu/Awesome-DeepSeek-Chinese/issues) 中提问，或者查看 [快速启动指南](./Quick_Start.md) 的避坑章节。
