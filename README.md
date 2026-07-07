# 🧰 表格急救箱 · Table Rescue Kit

> 把重复交给机器，把时间还给人。
> Let machines do the repetitive work.

**🚀 在线使用 / Use it now:** https://semiautohuman.github.io/table/

上传 Excel，一键处理；或者用一句话让 AI 处理任何表格问题——**数据不出你的电脑**。
Upload a spreadsheet and fix it in one click — or describe anything in one sentence and let AI handle it. **Your data never leaves your device.**

## ✨ 功能 Features

- ⚡ **一键文件功能**（100% 本地、断网可用）：名单核对、一键清理、整行去重、手机号打码、按列拆分工作表、多文件合并、A4 打印排版、打印版 Excel（自动缩放到一页）
- 🤖 **AI 模式**：一句话描述需求（改数据、修错、排版、美化都行），AI 生成处理代码，在你的浏览器本地执行全量数据
- 🧩 **8 个粘贴小工具**：微信接龙提取手机号、随机分组抽签、批量前后缀……
- 🌐 中文 / English

## 🔒 隐私 Privacy

- 文件在浏览器本地解析，从不上传 / Files are parsed locally, never uploaded
- AI 模式默认只发送「你的问题 + 表头」/ The AI sees your request and headers — never your data (full-data mode is opt-in)
- AI 生成的每一行代码透明可审 / Every line of generated code is auditable
- API key 只保存在你自己浏览器的本地存储 / Your API key lives only in your browser's local storage

## 🏗 架构 How it works

我们不把表格丢给大模型，而是给它搭了一套专为 Excel 打造的工作系统：

**结构诊断**（本地代码）→ **生成处理代码**（LLM，只看问题和表头）→ **本地沙箱执行全量数据** → **自动自检报告**

**AI 出智慧，代码出苦力。** The LLM writes the logic; deterministic code runs it locally on your full data — accurate at any scale, private by design.

## 📦 离线版 Offline version

整个应用就是一个 HTML 文件：打开[在线版](https://semiautohuman.github.io/table/)后 `Ctrl+S` 保存到桌面，双击即用（文件工具与粘贴小工具离线可用，AI 模式需联网）。

## 🔌 支持的模型服务 Supported providers

DeepSeek（默认）· Kimi · 智谱 GLM · 通义千问 · 豆包 · SiliconFlow · OpenAI · Claude · Gemini · Grok · OpenRouter · 任何 OpenAI 兼容接口

---

**半自动人类实验室 · Semiauto Human Lab** — 实验 002
每期实验解决一件重复劳动，做出来的工具免费放出。
微信公众号：半自动人类实验室
