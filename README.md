# OctapHub

**一站式 Windows 桌面 AI 创作工作台**：一个软件里完成 **AI 对话**、**AI 生图**、**AI 视频**，还能把生成结果直接写进 **Photoshop 画布**。对话与作品历史全部**本地保存**。

> 你只需自备 API Key，软件本身不含、也不出售任何模型额度。

---

## ✨ 主要功能

- **AI 对话**：流式打字机输出、多轮上下文、随时停止、历史留存。
- **AI 生图**：自动适配不同平台的两套生图协议，出图即落盘本地，可下载、可重开。
- **AI 视频**：文生视频 / 图生视频，异步任务自动轮询、下载落盘。
- **Photoshop 插件**：在 PS 面板内直接生图并写入画布图层。
- **本地持久化**：对话、生图、生视频历史存本地 SQLite，重启仍在。
- **密钥安全**：API Key 经 **Windows 凭据管理器加密存储**，绝不明文落盘、不上传。

---

## 🔌 支持的平台

采用「通用 OpenAI 兼容」设计，**适用大部分自定义 API 平台**：

- 内置预设：OpenRouter、硅基流动 SiliconFlow、DeepSeek、OneAPI / NewAPI（自建）等。
- 也支持你**手动添加任意 OpenAI 兼容的自定义中转平台**：填入 Base URL、API Key 与模型 id 即可使用。

> 软件只提供使用授权，**AI 能力需你自备各平台 API Key**。

---

## ⬇️ 下载安装

前往 **[Releases 页面](https://github.com/RoccoDannel/octaphub-download/releases/latest)** 下载：

| 文件 | 说明 |
|------|------|
| `YHhub_x.x.x_x64-setup.exe` | Windows 安装包（主程序），双击安装即用 |
| `YHub-Bridge-PS-Plugin.zip` | Photoshop 插件（可选，需要 PS 生图时安装） |

**Photoshop 插件安装**：解压后，用 Adobe UXP Developer Tool 加载 `manifest.json`，或放入 Photoshop 插件目录后重启 Photoshop。使用时需保持主程序 OctapHub 运行。

---

## 🚀 首次使用

1. 安装并启动 OctapHub。
2. 「设置 › 授权中心」→ 开始 7 天试用，或输入激活码。
3. 「设置 › 模型服务商」→ 选择或新增平台，填入 Base URL 与 API Key，测试连通、拉取/添加模型。
4. 回到「对话 / 生成 / 视频」开始创作。

---

## 🔐 授权说明

- 全功能 **7 天试用**（按设备）。
- 买断授权：Basic 绑 1 台设备、Pro 绑 3 台、Team 自定义设备数。
- 换设备时可在「授权中心」先「解绑本机」，释放名额。

---

## 💻 系统要求

- Windows 10 / 11（64 位）
- 首次运行需联网激活 / 开始试用；之后支持离线使用（定期联网校验）。
