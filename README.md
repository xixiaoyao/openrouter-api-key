# 🚀[TeamoRouter API](https://teamorouter.com/)-🚀 一个 API Key，接入全球LLM

# 热门大模型 API Key：Gemini API Key / OpenAI API Key / Anthropic API Key / ChatGPT API Key

## 🚀 一个 API Key，接入 Codex、Claude、Gemini 等热门大模型/Agent

[TeamoRouter](https://teamorouter.com/zh) 是面向开发者和 AI Agent 场景的 LLM Router。  
只需要一个 TeamoRouter API Key，就可以调用 GPT、Anthropic、Google Gemini 等热门大模型，适合 Codex、Claude Code、Gemini CLI、Cline、OpenCode、Cherry Studio 等开发工具和 Agent 客户端使用。

> 关键词：gemini api key / openai api key / anthropic api key / chatgpt api key / claude api key / ai api key / 大模型 api key / API 中转站

---

## 🔥 立即获取 API Key

👉 [点击获取 TeamoRouter API Key](https://teamorouter.com/dashboard?tab=api-keys)  
👉 [查看 TeamoRouter 官网](https://teamorouter.com/zh)  
👉 [查看 API 接入文档](https://teamorouter.com/zh/docs/api-integration)  
👉 [查看实时价格与模型折扣](https://teamorouter.com/zh)

---

## 📌 快速导航

### 一、获取 API Key

- [注册 / 登录 TeamoRouter](https://teamorouter.com/dashboard)
- [创建 API Key](https://teamorouter.com/dashboard?tab=api-keys)
- [购买额度](https://teamorouter.com/dashboard)
- [查看实时价格](https://teamorouter.com/zh)

### 二、热门客户端接入

- [Codex 桌面版接入教程](https://teamorouter.com/zh/docs/install-codex-desktop)
- [Codex 终端版接入教程](https://teamorouter.com/zh/docs/install-codex)
- [Claude Code 终端版接入教程](https://teamorouter.com/zh/docs/install-claude-code)
- [Claude Code 桌面版接入教程](https://teamorouter.com/zh/docs/install-claude-code-desktop)
- [VSCode + Cline 接入教程](https://teamorouter.com/zh/docs/install-vscode-cline)
- [Cherry Studio 接入教程](https://teamorouter.com/zh/docs/install-cherry-studio)
- [CC Switch 接入教程](https://teamorouter.com/zh/docs/install-cc-switch)
- [OpenClaw 接入教程](https://teamorouter.com/zh/docs/install-openclaw)
- [OpenCode 接入教程](https://teamorouter.com/zh/docs/install-opencode)
- [Gemini CLI 接入教程](https://teamorouter.com/zh/docs/install-gemini-cli)
- [WorkBuddy 接入教程](https://teamorouter.com/zh/docs/install-workbuddy)
- [Trae 接入教程](https://teamorouter.com/zh/docs/install-trae)

### 三、开发者 API 文档

- [API 手动配置](https://teamorouter.com/zh/docs/api-integration)
- [账单明细 FAQ](https://teamorouter.com/zh/docs/billing-faq)
- [下载 Teamo 客户端](https://teamorouter.com/zh/download)
- [邀请返现](https://teamorouter.com/zh/share)

---

## 💰 模型与定价

TeamoRouter 采用按量付费模式，按模型自动计价。

价格会根据上游模型成本和实时折扣变化，建议以官网实时价格为准。

👉 [查看实时价格](https://teamorouter.com/zh)

```Bash
| 模型 | 官方输入价 | 官方输出价 | TeamoRouter 输入价 | TeamoRouter 输出价 | 折扣 |
|---|---:|---:|---:|---:|---:|
| claude-opus-4-8 | $5.0000 | $25.0000 | $1.2050 | $6.0250 | 2.4 折 |
| claude-sonnet-5 | $3.0000 | $15.0000 | $0.6000 | $3.0000 | 2 折 |
| gpt-5.5 | $5.0000 | $30.0000 | $0.5450 | $3.2700 | 1 折 |
| gpt-5.4 | $2.5000 | $15.0000 | $0.2625 | $1.5750 | 1 折 |
| gpt-5.4-mini | $0.7500 | $4.5000 | $0.0855 | $0.5130 | 1.1 折 |
| gemini-3.1-pro-preview | $2.0000 | $12.0000 | $0.3320 | $1.9920 | 1.6 折 |
| gemini-3.5-flash | $1.5000 | $9.0000 | $0.3000 | $1.8000 | 2 折 |
```

---

## ⚡ 快速开始

### 1. 获取 API Key

访问 TeamoRouter 控制台创建 API Key：

👉 [获取 TeamoRouter API Key](https://teamorouter.com/dashboard?tab=api-keys)

API Key 示例：

```Bash
sk-teamo-xxxxxx
```

请妥善保管 API Key，不要提交到 GitHub、前端代码或公开仓库中。

---

### 2. 配置 Base URL

TeamoRouter 支持 OpenAI / Anthropic / Gemini 等协议。

如果你的项目兼容 OpenAI API，只需要替换 Base URL 和 API Key：

```Bash
Base URL: https://api.teamorouter.com/v1
API Key: sk-teamo-xxxxxx
```

---

### 3. 调用热门大模型

```Bash
curl https://api.teamorouter.com/v1/chat/completions \
  -H "Authorization: Bearer sk-teamo-xxxxxx" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gpt-5.5",
    "messages": [
      {
        "role": "user",
        "content": "Hello TeamoRouter"
      }
    ]
  }'
```

---

### 更多接入方式

- [Codex Desktop 接入教程](https://teamorouter.com/zh/docs/install-codex-desktop)
- [Claude Code 接入教程](https://teamorouter.com/zh/docs/install-claude-code)
- [Gemini CLI 接入教程](https://teamorouter.com/zh/docs/install-gemini-cli)

---

## ✅ 推荐链接

- TeamoRouter 官网：[https://teamorouter.com/zh](https://teamorouter.com/zh)
- 获取 API Key：[https://teamorouter.com/dashboard?tab=api-keys](https://teamorouter.com/dashboard?tab=api-keys)
- API 接入文档：[https://teamorouter.com/zh/docs/api-integration](https://teamorouter.com/zh/docs/api-integration)
- Codex Desktop 接入：[https://teamorouter.com/zh/docs/install-codex-desktop](https://teamorouter.com/zh/docs/install-codex-desktop)
- Claude Code 接入：[https://teamorouter.com/zh/docs/install-claude-code](https://teamorouter.com/zh/docs/install-claude-code)
- Gemini CLI 接入：[https://teamorouter.com/zh/docs/install-gemini-cli](https://teamorouter.com/zh/docs/install-gemini-cli)
- 邀请返现：[https://teamorouter.com/zh/share](https://teamorouter.com/zh/share)

---

## About

TeamoRouter 是一个面向开发者、AI Agent 和企业团队的 LLM Router。  
通过 [TeamoRouter 官网](https://teamorouter.com/zh)，你可以用一个 API Key 接入 OpenAI、Anthropic Claude、Google Gemini 等热门大模型，并在 Codex、Claude Code、Gemini CLI、Cline、OpenCode 等工具中快速使用。

链接：https://teamorouter.com

Tag:

 `codex api` · `openai api key` · `anthropic api key` · `chatgpt api key` · `claude api key` · `gpt api key` · `ai api key` · `llm api` · `api 中转站` · `大模型 api` · `claude code` · `gemini cli` · `openai compatible api` ·`gemini api key` 
