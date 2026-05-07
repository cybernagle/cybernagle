<p align="center">
  <img src="./images/bilibilinagle.png" alt="CyberNagle" width="120"/>
</p>

<h1 align="center">CyberNagle</h1>

<p align="center">
  <strong>🇬🇧 Building AI Agents for the Physical & Digital World</strong><br/>
  <strong>🇨🇳 构建连接物理世界与数字世界的 AI Agent 系统</strong>
</p>

---

## 🗺️ Agent Tech Roadmap / Agent 技术路线

```
                    ┌─────────────────┐
                    │   Memory CLI    │
                    │  共享记忆层       │
                    │  Shared Memory  │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
    ┌─────────▼────────┐    │    ┌─────────▼────────┐
    │    Car Agent      │    │    │   FingerSaver     │
    │  物理世界 Agent    │    │    │  效率 Agent        │
    │  Physical World   │    │    │  Efficiency Agent  │
    └──────────────────┘    │    └──────────────────┘
                            │
                  ┌─────────▼────────┐
                  │      Cos AI      │
                  │   Coding Agent   │
                  │   代码 Agent      │
                  └──────────────────┘
```

### 🚗 Car Agent — Physical World Agent / 物理世界 Agent

> **[Repository](https://github.com/cybernagle/car-agent)**

A 4WD Raspberry Pi smart car project — bringing AI into the physical world.

4WD 树莓派智能小车项目 — 将 AI 带入物理世界。

- **Hardware / 硬件**: Raspberry Pi 3B + TB6612 motor driver + 4x TT motors
- **Goal / 目标**: Voice-controlled autonomous vehicle with AI-powered decision making
- **Tech / 技术**: Python, GPIO, USB microphone + speaker, voice interaction
- **Vision / 愿景**: Embodied AI — agents that can see, hear, and move in the real world

### ✋ FingerSaver — Efficiency Agent / 效率 Agent

> **[Repository](https://github.com/cybernagle/fingersaver)**

Manage multiple coding agents through a split-pane terminal UI — stop babysitting your agents.

分屏终端 UI 管理多个 coding agent — 不用再盯着你的 agent。

- **Architecture / 架构**: Go + Bubbletea TUI + tmux, Chat Pane (40%) + Tmux Viewer (60%)
- **Multi-Agent / 多 Agent**: Claude Code, GitHub Copilot — run them in parallel
- **LLM Orchestrator / LLM 编排器**: Auto-routes tasks to the best agent via @mention
- **Cross-Agent Relay / 跨 Agent 中继**: Messages, hooks, persistent chat sessions
- **Deploy / 部署**: `brew install cybernagle/tap/fingersaver`

### 🧠 Memory CLI — Shared Memory Layer / 共享记忆层

> *Coming Soon / 即将推出*

A shared memory system that connects all CyberNagle agents — one memory, many agents.

连接所有 CyberNagle Agent 的共享记忆系统 — 一份记忆，多个 Agent。

- **Unified Context / 统一上下文**: All agents share the same knowledge base
- **Cross-Agent Memory / 跨 Agent 记忆**: Car Agent learns from coding sessions; FingerSaver remembers physical world experiments
- **Local-First / 本地优先**: Your data stays on your machine

### 🤖 Cos AI — Coding Agent / 代码 Agent

> **[Repository](https://github.com/cybernagle/cos)**

A Go-based AI coding agent with CLI and BubbleTea TUI interfaces.

Go 实现的 AI coding agent，支持 CLI 和 BubbleTea TUI 两种界面。

- **Dual Mode / 双模式**: CLI (lightweight) + BubbleTea UI (interactive)
- **Streaming / 流式输出**: Real-time Claude API streaming
- **Tool System / 工具系统**: read, write, bash, ls — with permission control
- **Deploy / 部署**: `brew install cybernagle/cos/cos`

---

## 🛠️ Other Projects / 其他项目

| Project | Description |
|---------|-------------|
| [OptiTranslate](https://github.com/cybernagle/OptiTranslate) | macOS menu-bar AI translator — Opt+Space to translate, saves to Markdown |
| [Kokoros](https://github.com/cybernagle/Kokoros) | Kokoro TTS in Rust — insanely fast, realtime text-to-speech |
| [build-ai-body](https://github.com/cybernagle/build-ai-body) | 给 AI 做身体 — 微信公众号内容归档 |

---

## 📡 Philosophy / 理念

```
Physical World ←→ Agent ←→ Digital World
    物理世界      ←→ Agent ←→  数字世界
```

We believe the future of AI is **embodied agents** that bridge the physical and digital worlds. Each agent specializes in one domain, but they share a common memory and coordination layer.

我们相信 AI 的未来是**具身智能 Agent**，连接物理世界和数字世界。每个 Agent 专精一个领域，但共享统一的记忆和协调层。

---

<p align="center">
  <sub>Built with ❤️ by <a href="https://github.com/cybernagle">CyberNagle</a></sub>
</p>
