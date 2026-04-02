<div align="center">

> **🐍 Looking for the Python implementation?**
> 
> **[👉 Check out claude-code-python](https://github.com/mimran-khan/claude-code-python)** - Complete Python port with 1,805 modules, 149k lines, 925 tests

<br>

<img src="https://img.shields.io/badge/🔓_LEAKED-Claude_Code-FF0000?style=for-the-badge&labelColor=000000" alt="Leaked" width="300">

<br><br>

# Claude Code Source

##### *Reverse-engineered from leaked TypeScript source*

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

[![Python 3.11+](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Tests](https://img.shields.io/badge/Tests-925_passing-4CAF50?style=flat-square&logo=pytest&logoColor=white)](./claude-code-python/tests/)
[![Lines](https://img.shields.io/badge/Lines-149k+-blue?style=flat-square)](./claude-code-python/src/)
[![License](https://img.shields.io/badge/License-Educational-orange?style=flat-square)](./claude-code-python/LICENSE)

<br>

[Background](#-background) · [Disclaimer](#%EF%B8%8F-disclaimer) · [Installation](#-installation) · [Architecture](#-architecture) · [Documentation](#-documentation)

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

## 📖 Background

### The Leak

On March 31, 2026, Anthropic accidentally published their Claude Code npm package with source maps included. This exposed:

- **512,000+ lines** of TypeScript source code
- **1,900+ files** revealing the complete architecture
- **40+ agent tools** and their implementations
- **85+ slash commands** with internal logic
- **44+ feature flags** including unreleased features

### The Python Port

This repository represents a **complete, line-by-line migration** of the leaked TypeScript codebase to Python. The goal is purely educational—to help developers understand:

- How production agentic AI systems are built
- Tool-use patterns and orchestration
- Context management at scale
- MCP (Model Context Protocol) implementation

<br>

---

<br>

## 🚀 The Migration

<table>
<tr>
<td width="50%">

### 📊 By the Numbers

| Metric | Value |
|:-------|------:|
| Python modules | **1,805** |
| Lines of code | **149,032** |
| Unit tests | **925** |
| Tools ported | **88** |
| Services ported | **40+** |
| Commands ported | **85+** |

</td>
<td width="50%">

### ⚡ What's Included

- ✅ Full query engine with tool-use loop
- ✅ All 88 agent tools (file, shell, web, MCP)
- ✅ Complete service layer (API, OAuth, MCP)
- ✅ Working CLI with interactive mode
- ✅ Comprehensive test suite
- ✅ Type hints throughout

</td>
</tr>
</table>

<br>

---

<br>

## 🎯 Why Python?

Claude Code is an exceptional piece of engineering, but the original is locked to Node.js. This port enables:

<br>

<table>
<tr>
<td align="center" width="25%">
<br>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="48">
<br><br>
<b>Python Developers</b>
<br>
<sub>Study in your native language</sub>
<br><br>
</td>
<td align="center" width="25%">
<br>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="48">
<br><br>
<b>Data Scientists</b>
<br>
<sub>Explore in notebooks</sub>
<br><br>
</td>
<td align="center" width="25%">
<br>
🔬
<br><br>
<b>Researchers</b>
<br>
<sub>Analyze agent patterns</sub>
<br><br>
</td>
<td align="center" width="25%">
<br>
🎓
<br><br>
<b>Students</b>
<br>
<sub>Learn from production code</sub>
<br><br>
</td>
</tr>
</table>

<br>

---

<br>

## 📦 Installation

> **Note**: This is for educational study only. For actual use, please purchase Claude Code from Anthropic.

### Requirements

- Python 3.11 or higher
- An Anthropic API key (for testing)

### Setup

```bash
# Clone the repository
git clone https://github.com/mimran-khan/claude-code-source.git
cd claude-code-source/claude-code-python

# Create and activate virtual environment
python3.11 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install the package
pip install -e ".[dev]"

# Set your API key (for testing)
export ANTHROPIC_API_KEY="sk-ant-..."
```

### Verify Installation

```bash
claude --version
claude doctor
```

<br>

---

<br>

## 💻 Usage

### Command Line

```bash
# Start interactive chat
claude

# One-shot query (print mode)
claude -p "Explain what this codebase does"

# Run diagnostics
claude doctor
```

### Python API

```python
import asyncio
from claude_code.core.query_engine import QueryEngine, QueryEngineConfig

async def main():
    engine = QueryEngine(QueryEngineConfig(
        cwd="/path/to/your/project",
        tools=[],
        max_tokens=4096,
    ))
    
    response = await engine.query("What files are in this directory?")
    print(response)

asyncio.run(main())
```

<br>

---

<br>

## 🛠️ Tools

All 88 tools from the original Claude Code have been ported:

| Category | Tools |
|:---------|:------|
| **File Operations** | `Read`, `Write`, `Edit`, `MultiEdit`, `Glob`, `Grep`, `Search` |
| **Shell Execution** | `Bash`, `PowerShell`, subprocess with timeout/abort |
| **Web Access** | `WebFetch`, `WebSearch` |
| **MCP Protocol** | Full client implementation, tool discovery, OAuth |
| **Agent System** | `AgentTool`, `TaskTool`, sub-agent spawning |
| **Notebooks** | Jupyter notebook reading and editing |
| **Memory** | Todo lists, task management, session state |
| **Planning** | Plan mode, thinking tools, mode switching |

<br>

---

<br>

## 🏗️ Architecture

```
claude-code-python/src/claude_code/
├── core/                 # Query engine, tool contracts, context
├── engine/               # High-level SDK interface
├── cli/                  # Typer-based command line interface
├── tools/                # 88 tool implementations
│   ├── bash_tool/
│   ├── file_read_tool/
│   ├── grep_tool/
│   ├── mcp_tool/
│   └── ...
├── services/             # External integrations
│   ├── api/              # Anthropic API client
│   ├── mcp/              # Model Context Protocol
│   ├── compact/          # Context compaction
│   ├── oauth/            # Authentication
│   └── ...
├── hooks/                # Event system
├── commands/             # Slash commands (/commit, /review, etc.)
├── bridge/               # Remote session management
└── utils/                # Shared utilities (500+ modules)
```

### Request Flow

```
┌─────────────┐     ┌──────────────┐     ┌─────────────────┐
│  User Input │────▶│ Query Engine │────▶│  Anthropic API  │
└─────────────┘     └──────────────┘     └─────────────────┘
                           │                      │
                           │                      ▼
                           │              ┌───────────────┐
                           │              │ Tool Use?     │
                           │              └───────────────┘
                           │                 Yes │    │ No
                           │                     ▼    │
                           │              ┌──────────┐│
                           │◀─────────────│ Execute  ││
                           │              │   Tool   ││
                           │              └──────────┘│
                           │                          ▼
                           │                   ┌──────────┐
                           └──────────────────▶│ Response │
                                               └──────────┘
```

<br>

---

<br>

## 📚 Documentation

| Document | Description |
|:---------|:------------|
| [ARCHITECTURE.md](./claude-code-python/docs/ARCHITECTURE.md) | System design, component relationships |
| [TOOLS.md](./claude-code-python/docs/TOOLS.md) | Complete tool reference with examples |
| [SERVICES.md](./claude-code-python/docs/SERVICES.md) | Service layer documentation |
| [API.md](./claude-code-python/docs/API.md) | Python API reference |
| [DATA_FLOW.md](./claude-code-python/docs/DATA_FLOW.md) | Request/response flow diagrams |
| [CHANGELOG.md](./claude-code-python/CHANGELOG.md) | Version history |

<br>

---

<br>

## 🧪 Development

### Running Tests

```bash
cd claude-code-python

# All tests
pytest

# With coverage report
pytest --cov=src/claude_code --cov-report=html

# Skip slow integration tests
pytest -m "not integration"
```

### Code Quality

```bash
# Lint and format
ruff check src tests --fix
ruff format src tests

# Type checking
mypy src
```

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
<img src="https://img.shields.io/github/commit-activity/m/mimran-khan/claude-code-source?style=for-the-badge&logo=github&label=Commits/Month&color=green" alt="Commit Activity">

<br><br>

<img src="https://img.shields.io/github/issues/mimran-khan/claude-code-source?style=flat-square&logo=github&label=Issues" alt="Issues">
<img src="https://img.shields.io/github/issues-pr/mimran-khan/claude-code-source?style=flat-square&logo=github&label=Pull%20Requests" alt="PRs">
<img src="https://img.shields.io/github/contributors/mimran-khan/claude-code-source?style=flat-square&logo=github&label=Contributors" alt="Contributors">

<br><br>

**[⭐ Star this repo](https://github.com/mimran-khan/claude-code-source) · [🍴 Fork](https://github.com/mimran-khan/claude-code-source/fork) · [🐛 Report Issue](https://github.com/mimran-khan/claude-code-source/issues) · [💬 Discussions](https://github.com/mimran-khan/claude-code-source/discussions)**

<br>

---

<br>

**📚 For Educational Purposes Only**

<br>

*Not affiliated with Anthropic*

</div>
