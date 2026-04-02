<div align="center">

> **🐍 Looking for the Python implementation?**
> 
> **[👉 Check out claude-code-python](https://github.com/mimran-khan/claude-code-python)** - Complete Python port with 1,805 modules, 149k lines, 925 tests

<br>

<img src="https://img.shields.io/badge/🔓_LEAKED-Claude_Code-FF0000?style=for-the-badge&labelColor=000000" alt="Leaked" width="300">

<br><br>

# Claude Code Source

### The Complete Leaked TypeScript Source Code

##### *Extracted from Anthropic's npm package via source maps*

<br>

<a href="https://github.com/mimran-khan/claude-code-source/stargazers">
  <img src="https://img.shields.io/github/stars/mimran-khan/claude-code-source?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=yellow" alt="Stars">
</a>
<a href="https://github.com/mimran-khan/claude-code-source/network/members">
  <img src="https://img.shields.io/github/forks/mimran-khan/claude-code-source?style=for-the-badge&logo=github&logoColor=white&label=Forks&color=blue" alt="Forks">
</a>
<a href="https://github.com/mimran-khan/claude-code-source/watchers">
  <img src="https://img.shields.io/github/watchers/mimran-khan/claude-code-source?style=for-the-badge&logo=github&logoColor=white&label=Watchers&color=green" alt="Watchers">
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=mimran-khan-claude-code-source&label=Profile%20Views&color=blueviolet&style=for-the-badge" alt="Profile Views">

<br><br>

[![TypeScript](https://img.shields.io/badge/TypeScript-99.5%25-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Files](https://img.shields.io/badge/Files-1,900+-blue?style=flat-square)](./tools/)
[![Lines](https://img.shields.io/badge/Lines-512k+-orange?style=flat-square)](./QueryEngine.ts)
[![License](https://img.shields.io/badge/License-Educational-red?style=flat-square)](#-legal-notice)

<br>

[Overview](#-overview) · [Disclaimer](#%EF%B8%8F-disclaimer) · [Architecture](#-architecture) · [Tools](#-tools) · [Commands](#%EF%B8%8F-commands)

</div>

<br>

---

<br>

## ⚠️ DISCLAIMER

> **📚 EDUCATIONAL & RESEARCH PURPOSES ONLY**
>
> This repository contains source code that was **accidentally leaked** by Anthropic through their npm package (version 2.1.88) on **March 31, 2026**. A source map file (`.map`) was inadvertently bundled into production, allowing complete reconstruction of the original TypeScript source.
>
> <br>
>
> | ❌ DO NOT | ✅ DO |
> |:----------|:------|
> | Use this code for commercial purposes | Use for learning and research |
> | Create competing products based on this code | Study AI coding assistant architecture |
> | Circumvent Anthropic's security measures | Understand agentic tool systems |
> | Redistribute for profit | Contribute educational improvements |
>
> <br>
>
> **This code is proprietary and owned by Anthropic. All rights reserved by Anthropic.**

<br>

---

<br>

## 🌟 Overview

**Claude Code** is Anthropic's official agentic coding assistant — a powerful AI-powered CLI tool that can:

- 🖥️ Read, write, and edit files in your codebase
- ⚡ Execute shell commands and scripts
- 🔍 Search code with regex and glob patterns
- 🤖 Spawn sub-agents for parallel work
- 🌐 Fetch web content and search the internet
- 🔌 Connect to external tools via MCP (Model Context Protocol)
- 📋 Manage tasks, todos, and session state
- 🎨 Provide beautiful terminal UI with themes

<br>

---

<br>

## 📊 What's Inside

| Metric | Count |
|:-------|------:|
| **TypeScript Files** | 1,900+ |
| **Lines of Code** | 512,000+ |
| **Agent Tools** | 40+ |
| **Slash Commands** | 85+ |
| **Feature Flags** | 44+ |
| **React Components** | 146 |

<br>

---

<br>

## 🏗️ Architecture

```
claude-code-source/
├── QueryEngine.ts        # 🧠 Core LLM engine (46K lines!)
├── Tool.ts               # 🔧 Tool system base
├── Task.ts               # 📋 Task management
├── commands/             # ⌨️ 85+ slash commands
├── tools/                # 🛠️ 40+ agent tools
├── components/           # 🎨 React UI components
├── services/             # 🔌 External integrations
│   ├── api/              # Anthropic API
│   ├── mcp/              # Model Context Protocol
│   └── ...
├── hooks/                # ⚡ React hooks
├── bridge/               # 🌉 Remote session management
├── utils/                # 🧰 Shared utilities (330+ files)
└── ...
```

### Key Components

| Component | Lines | Purpose |
|:----------|------:|:--------|
| QueryEngine | 46,000+ | Core agentic loop, tool orchestration, context management |
| Tool System | 15,000+ | 40+ tools for file ops, search, execution, web |
| Bridge | 8,000+ | Remote sessions via WebSocket/SSE |
| Skills | 5,000+ | Prompt-based extensibility |

<br>

---

<br>

## 🛠️ Tools (40+)

| Category | Tools |
|:---------|:------|
| **File Operations** | FileReadTool, FileWriteTool, FileEditTool, NotebookEditTool |
| **Search** | GlobTool, GrepTool, LSPTool |
| **Execution** | BashTool, PowerShellTool, AgentTool |
| **Web** | WebFetchTool, WebSearchTool, MCPTool |
| **Tasks** | TodoWriteTool, TaskCreateTool, TaskUpdateTool |

<br>

---

<br>

## ⌨️ Commands (85+)

| Category | Examples |
|:---------|:---------|
| **Git** | `/commit`, `/pr_comments`, `/review` |
| **Session** | `/compact`, `/clear`, `/resume` |
| **Config** | `/config`, `/permissions`, `/theme` |
| **Development** | `/doctor`, `/mcp`, `/skills` |
| **Hidden** | `/buddy` 🐾, `/dream`, `/ultraplan` |

<br>

---

<br>

## 🚩 Feature Flags (44+)

| Flag | Purpose |
|:-----|:--------|
| `KAIROS` | Full autonomous agent mode |
| `PROACTIVE` | Proactive assistance |
| `BUDDY` | 🐾 Digital pet system! |
| `VOICE_MODE` | Voice input/output |
| `CACHED_MICROCOMPACT` | Context optimization |

<br>

---

<br>

## 🔗 Related

- **[🐍 Python Port](https://github.com/mimran-khan/claude-code-python)** - Complete Python implementation
- **[🌐 Live Analysis](https://mimran-khan.github.io/claude-code-source/)** - Interactive website
- **[📦 Official CLI](https://github.com/anthropics/claude-code)** - Anthropic's official repo
- **[📚 Official Docs](https://code.claude.com/docs/en/overview)** - Claude Code documentation

<br>

---

<br>

## 📜 Legal Notice

This source code is **proprietary** and owned by **Anthropic**. 

This repository exists **strictly for educational and research purposes**. The maintainers do not encourage or condone any commercial use or redistribution of this code.

**All rights reserved by Anthropic.**

If you are from Anthropic and wish to have this repository removed, please open an issue or contact the maintainers directly.

<br>

---

<br>

<div align="center">

## 📈 Repository Stats

<br>

<img src="https://img.shields.io/github/repo-size/mimran-khan/claude-code-source?style=for-the-badge&logo=github&label=Repo%20Size&color=orange" alt="Repo Size">
<img src="https://img.shields.io/github/last-commit/mimran-khan/claude-code-source?style=for-the-badge&logo=github&label=Last%20Commit&color=purple" alt="Last Commit">

<br><br>

**[⭐ Star](https://github.com/mimran-khan/claude-code-source) · [🍴 Fork](https://github.com/mimran-khan/claude-code-source/fork) · [🐛 Report Issue](https://github.com/mimran-khan/claude-code-source/issues)**

<br>

---

<br>

**📚 For Educational Purposes Only**

<br>

*Not affiliated with Anthropic*

</div>
