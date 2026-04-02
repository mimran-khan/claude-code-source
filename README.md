<div align="center">

### [📺 **VIEW LIVE INTERACTIVE ANALYSIS →**](https://mimran-khan.github.io/claude-code-source/)

**🐍 [Python Port](https://github.com/mimran-khan/claude-code-python)** - Complete Python implementation (1,805 modules, 149k lines, 925 tests)

---

<img src="https://img.shields.io/badge/🔓_LEAKED-Claude_Code-FF0000?style=for-the-badge&labelColor=000000" alt="Leaked" width="280">

# Claude Code Source

**The Complete Leaked TypeScript Source Code**

*Extracted from Anthropic's npm package via source maps*

[![Stars](https://img.shields.io/github/stars/mimran-khan/claude-code-source?style=flat-square&logo=github&label=Stars&color=yellow)](https://github.com/mimran-khan/claude-code-source/stargazers)
[![Forks](https://img.shields.io/github/forks/mimran-khan/claude-code-source?style=flat-square&logo=github&label=Forks&color=blue)](https://github.com/mimran-khan/claude-code-source/network/members)
[![Watchers](https://img.shields.io/github/watchers/mimran-khan/claude-code-source?style=flat-square&logo=github&label=Watchers&color=green)](https://github.com/mimran-khan/claude-code-source/watchers)
[![Views](https://komarev.com/ghpvc/?username=mimran-khan-claude-code-source&label=Views&color=blueviolet&style=flat-square)](https://github.com/mimran-khan/claude-code-source)

[![TypeScript](https://img.shields.io/badge/TypeScript-99.5%25-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Files](https://img.shields.io/badge/Files-1,900+-blue?style=flat-square)](./tools/)
[![Lines](https://img.shields.io/badge/Lines-512k+-orange?style=flat-square)](./QueryEngine.ts)
[![License](https://img.shields.io/badge/License-Educational-red?style=flat-square)](#legal-notice)

[Overview](#overview) · [Disclaimer](#disclaimer) · [Architecture](#architecture) · [Tools](#tools) · [Commands](#commands)

</div>

---

## ⚠️ DISCLAIMER

> **📚 EDUCATIONAL & RESEARCH PURPOSES ONLY**
>
> This repository contains source code that was **accidentally leaked** by Anthropic through their npm package (version 2.1.88) on **March 31, 2026**. A source map file was inadvertently bundled into production.
>
> | ❌ DO NOT | ✅ DO |
> |:----------|:------|
> | Use for commercial purposes | Use for learning and research |
> | Create competing products | Study AI coding assistant architecture |
> | Redistribute for profit | Understand agentic tool systems |
>
> **This code is proprietary and owned by Anthropic. All rights reserved.**

---

## 🌟 Overview

**Claude Code** is Anthropic's agentic coding assistant that can read/write files, execute shell commands, search code, spawn sub-agents, fetch web content, and connect to external tools via MCP.

| Metric | Count |
|:-------|------:|
| TypeScript Files | 1,900+ |
| Lines of Code | 512,000+ |
| Agent Tools | 40+ |
| Slash Commands | 85+ |
| Feature Flags | 44+ |

---

## 🏗️ Architecture

```
claude-code-source/
├── QueryEngine.ts        # 🧠 Core LLM engine (46K lines)
├── Tool.ts / Task.ts     # 🔧 Tool & task system
├── commands/             # ⌨️ 85+ slash commands
├── tools/                # 🛠️ 40+ agent tools
├── components/           # 🎨 React UI (146 components)
├── services/             # 🔌 API, MCP, OAuth
├── hooks/                # ⚡ React hooks
├── bridge/               # 🌉 Remote sessions
└── utils/                # 🧰 Utilities (330+ files)
```

---

## 🛠️ Tools & Commands

| Tools | Commands | Feature Flags |
|:------|:---------|:--------------|
| FileRead, FileWrite, FileEdit | /commit, /review, /pr_comments | KAIROS (autonomous mode) |
| Glob, Grep, LSP | /compact, /clear, /resume | PROACTIVE |
| Bash, PowerShell, Agent | /config, /permissions, /theme | BUDDY 🐾 |
| WebFetch, WebSearch, MCP | /doctor, /mcp, /skills | VOICE_MODE |
| TodoWrite, TaskCreate | /buddy, /dream, /ultraplan | CACHED_MICROCOMPACT |

---

## 🔗 Related

[🌐 Live Analysis](https://mimran-khan.github.io/claude-code-source/) · [🐍 Python Port](https://github.com/mimran-khan/claude-code-python) · [📦 Official CLI](https://github.com/anthropics/claude-code) · [📚 Docs](https://docs.anthropic.com/en/docs/claude-code)

---

## 📜 Legal Notice

This source code is **proprietary** and owned by **Anthropic**. This repository exists strictly for educational purposes. If you are from Anthropic and wish to have this removed, please open an issue.

---

<div align="center">

[![Repo Size](https://img.shields.io/github/repo-size/mimran-khan/claude-code-source?style=flat-square&label=Size)](https://github.com/mimran-khan/claude-code-source)
[![Last Commit](https://img.shields.io/github/last-commit/mimran-khan/claude-code-source?style=flat-square&label=Updated)](https://github.com/mimran-khan/claude-code-source)

**📚 For Educational Purposes Only** · *Not affiliated with Anthropic*

</div>
