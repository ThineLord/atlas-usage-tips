# Atlas 使用指南 📘

欢迎使用 Atlas 浏览器，本指南将详细介绍如何安装、设置、使用其核心功能，并提供使用技巧。Atlas 集成 ChatGPT，可帮助你更高效地完成各种任务。

## 目录
- [安装和登录](#安装和登录)
- [核心功能](#核心功能)
- [搜索与浏览](#搜索与浏览)
- [标签管理](#标签管理)
- [内存和隐私控制](#内存和隐私控制)
- [自动填表和下载管理](#自动填表和下载管理)
- [代理模式 (Agent Mode)](#代理模式-agent-mode)
- [使用技巧](#使用技巧)
- [资源链接](#资源链接)

## 安装和登录

Atlas 目前支持 macOS（截至 2025 年 10 月 21 日），你可以从 [ChatGPT 官网](https://chat.openai.com) 下载并安装。首次启动时可以选择导入其他浏览器的书签、保存的密码和浏览历史，并使用你的 ChatGPT 帐号登录。

## 核心功能

Atlas 将 ChatGPT 智能体深度集成到浏览器，提供以下核心功能：

- **智能搜索与摘要 🧠**：使用自然语言输入搜索内容，Atlas 会自动总结网页信息并提供引用链接 ([openai.com](https://openai.com/index/introducing-chatgpt-atlas/)) 。在搜索页面上直接与结果对话，获取更深入的解释。
- **内置记忆 📌**：浏览器可以选择性地记住你在网上的活动，用于改进助手的表现。记忆是可选的，用户可随时删除或管理 ([openai.com](https://openai.com/index/introducing-chatgpt-atlas/)) 。
- **任务助手 🧑‍💼**：可以让助手帮你完成表单、订票、购物等任务，甚至支持自动完成步骤（在最后一步前会请求确认）。
- **代理模式 (Agent Mode) 🚀**：使助理能够在选定的网站上自动执行多步骤任务，如填表、订座等，目前适用于 Plus、Pro 和 Business 用户 ([openai.com](https://openai.com/index/introducing-chatgpt-atlas/)) 。

## 搜索与浏览

使用 Atlas 进行搜索和浏览时，可遵循以下方法：

1. **全局搜索框 🔍**：在地址栏或搜索栏直接输入自然语言查询。例如 “查找今年洛杉矶最佳餐厅”。Atlas 会显示聚合搜索结果并提供快速摘要。
2. **在网页中查找 ⌘/Ctrl + F**：若需查找页面内的某个词，可使用 Command/Ctrl + F 快捷键。Atlas 还支持在多个标签页中同时搜索 ([help.openai.com](https://help.openai.com/en/articles/12628371-browsing-the-web-with-chatgpt-atlas)) 。
3. **对话增强**：点击搜索结果中某条链接右侧的聊天图标，开启与 ChatGPT 的实时对话，以解释和分析内容。
4. **自然语言导航**：你可以直接在搜索框中输入 “打开 GitHub 并搜索 Atlas 项目”，助手会自动执行。

## 标签管理

Atlas 提供强大的标签管理功能：

- **多标签工作区 🗂️**：可以创建不同工作区以隔离项目或任务。通过侧边栏切换工作区 ([help.openai.com](https://help.openai.com/en/articles/12628371-browsing-the-web-with-chatgpt-atlas#:~:text=location,helpful%3F%20%20Submit%20Search%20the)) 。
- **快速切换标签**：使用快捷键 `Cmd/Ctrl + 1-9` 在常用标签间切换。
- **拆分视图**：支持将一个标签固定并在右侧打开新标签，便于比较不同页面。

## 内存和隐私控制

Atlas 的记忆功能可帮助模型更好地理解你的偏好，但完全由用户掌控：

- **开启/关闭记忆 🧠**：在设置中可以选择开启或关闭浏览历史记忆。关闭记忆时，所有浏览数据仅存储在本地，不会用于个性化。
- **删除和管理记忆 🧹**：在记忆管理界面可以浏览已保存的记忆片段，选择删除单个或全部记忆 ([openai.com](https://openai.com/index/introducing-chatgpt-atlas/)) 。
- **隐身模式 🕵️**：开启隐身模式时，浏览器不会保存任何历史记录或表单数据。

## 自动填表和下载管理

Atlas 内置的自动填表和下载管理可以简化你的日常任务：

- **表单自动填充 ✍️**：在安全的情况下，助手可以自动填写网页表单（如订票、预约等），但总会在提交前向你确认 ([help.openai.com](https://help.openai.com/en/articles/12628371-browsing-the-web-with-chatgpt-atlas#:~:text=mute%20noisy%20sites%2C%20or%20move,are%20provided%20by%20websites)) 。
- **文件下载管理 📂**：下载的文件会统一管理，你可以在下载管理器中查看、暂停或取消下载。与传统浏览器类似，还支持设置默认下载目录。
- **跨设备同步**：登录同一账号后，书签和记忆可在多设备之间同步。

## 代理模式 (Agent Mode)

代理模式是 Atlas 的亮点，它允许 ChatGPT 自动完成复杂流程，例如预订餐馆或填写注册表。这一模式在某些功能中仍处于测试阶段，目前面向 Plus、Pro、Business 用户 ([openai.com](https://openai.com/index/introducing-chatgpt-atlas/)) 。

使用方法：

1. **启用代理模式**：在设置中开启 “Agent Mode”。  
2. **发出任务指令**：通过自然语言描述目标，例如：“帮我在 OpenTable 预约下周五晚上 7 点在洛杉矶的某日料店”。  
3. **助手执行任务**：Atlas 会自动打开相关网站、搜索餐厅、选择时间并填写表单，直到最后一步前停止并请求你的确认，然后再提交。  
4. **管理自动执行权限**：你可以指定哪些网站允许代理自动操作，其他网站则只会提供手动指导。

## 使用技巧

- **简洁清晰的指令 💡**：用自然语言描述你的目标越具体，助手完成任务的效率越高。
- **逐步操作**：如果任务复杂，可以将指令分成几个步骤，例如先让助手搜索餐厅，再选择时间、提交预订。
- **充分利用引用**：阅读助手给出的摘要时，可以点击引用跳转到原文，以获取完整信息 ([openai.com](https://openai.com/index/introducing-chatgpt-atlas/)) 。
- **定期清理记忆**：为了保障隐私，建议定期检查并清理不再需要的记忆。
- **尝试工作区**：将不同项目放在不同工作区，既能保持条理，也能更专注。

## 资源链接

- 🌐 [Atlas 官方公告](https://openai.com/blog/introducing-chatgpt-atlas) – 了解产品背景与功能 ([openai.com](https://openai.com/index/introducing-chatgpt-atlas/)) 。  
- 📖 [Atlas 浏览帮助文档](https://help.openai.com/en/articles/123456789-browsing-with-atlas) – 学习如何在 Atlas 中搜索、管理标签和工作区 ([help.openai.com](https://help.openai.com/en/articles/12628371-browsing-the-web-with-chatgpt-atlas)) 。  
- 💼 [OpenAI 支持页面](https://help.openai.com) – 获取常见问题解答和支持。  

---

希望本指南能够帮助你快速上手并充分利用 Atlas 的强大功能，探索更高效的工作方式。如有建议或发现错误，欢迎提交 issue 或 pull request 共建这个项目！🚀
