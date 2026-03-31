<div align="center">

<img src="./assets/header-banner.png" alt="Anthropic Claude Code Leaked" width="100%">

<br>

<h1>
  <img src="https://img.shields.io/badge/🔓_LEAKED-Source_Code-FF0000?style=for-the-badge&labelColor=000000" alt="Leaked">
  <img src="https://img.shields.io/badge/512K+-Lines_of_Code-FF6B6B?style=for-the-badge&labelColor=1a1a2e" alt="Lines">
  <img src="https://img.shields.io/badge/1,900+-Files-FF6B6B?style=for-the-badge&labelColor=1a1a2e" alt="Files">
</h1>

</div>

<p align="center">
  <b>🚨 The Complete Decompiled Source of Anthropic's Agentic Coding CLI 🚨</b>
</p>

<p align="center">
  <code>512,000+ lines of TypeScript</code> • <code>1,900+ files</code> • <code>40+ Agent Tools</code> • <code>85+ Commands</code>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Leaked_On-March_31,_2026-red?style=flat-square" alt="Date">
  <img src="https://img.shields.io/badge/npm_Package-v2.1.88-orange?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/Source_Map-59.8_MB-yellow?style=flat-square" alt="Size">
</p>

<p align="center">
  <a href="#-overview"><img src="https://img.shields.io/badge/Overview-blue?style=flat-square" alt="Overview"></a>
  <a href="#-architecture"><img src="https://img.shields.io/badge/Architecture-green?style=flat-square" alt="Architecture"></a>
  <a href="#-tools"><img src="https://img.shields.io/badge/Tools-orange?style=flat-square" alt="Tools"></a>
  <a href="#-commands"><img src="https://img.shields.io/badge/Commands-purple?style=flat-square" alt="Commands"></a>
  <a href="#-feature-flags"><img src="https://img.shields.io/badge/Feature_Flags-red?style=flat-square" alt="Feature Flags"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" alt="Bun">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Lines_of_Code-512K+-FF4136?style=for-the-badge" alt="LOC">
  <img src="https://img.shields.io/badge/License-Proprietary-gray?style=for-the-badge" alt="License">
</p>

---

<div align="center">

## ⚠️ IMPORTANT DISCLAIMER

</div>

> **📚 EDUCATIONAL & RESEARCH PURPOSES ONLY**
>
> This repository contains source code that was **accidentally leaked** by Anthropic through their npm package (version 2.1.88) on **March 31, 2026**. A source map file (`.map`) was inadvertently bundled into production, allowing complete reconstruction of the original TypeScript source.
>
> - ❌ **DO NOT** use this code for commercial purposes
> - ❌ **DO NOT** create competing products based on this code  
> - ❌ **DO NOT** use this to circumvent Anthropic's security measures
> - ✅ **DO** use for learning, research, and understanding AI coding assistants
>
> **This code is proprietary and owned by Anthropic. All rights reserved by Anthropic.**

---

<div align="center">

## 📊 At a Glance

</div>

<table align="center">
<tr>
<td align="center"><b>📁 Files</b><br><code>1,900+</code></td>
<td align="center"><b>📝 Lines</b><br><code>512,000+</code></td>
<td align="center"><b>🔧 Tools</b><br><code>40+</code></td>
<td align="center"><b>⌨️ Commands</b><br><code>85+</code></td>
<td align="center"><b>🚩 Flags</b><br><code>44+</code></td>
</tr>
</table>

---

## 📖 Table of Contents

<details>
<summary>Click to expand</summary>

- [Overview](#-overview)
- [How It Leaked](#-how-it-leaked)
- [Architecture](#-architecture)
- [Directory Structure](#-directory-structure)
- [Core Engine](#-core-engine)
- [Tools](#-tools)
- [Commands](#-commands)
- [Feature Flags](#-feature-flags)
- [Skills System](#-skills-system)
- [MCP Integration](#-mcp-integration)
- [Security](#-security)
- [Easter Eggs](#-easter-eggs)
- [Model Information](#-model-information)
- [Tech Stack](#-tech-stack)
- [Internal Codenames](#-internal-codenames)
- [References](#-references)

</details>

---

## 🌟 Overview

**Claude Code** is Anthropic's official agentic coding assistant — a powerful AI-powered tool that can:

```
┌────────────────────────────────────────────────────────────────────────┐
│                                                                        │
│   🖥️  Read, write, and edit files in your codebase                    │
│   ⚡  Execute shell commands and scripts                               │
│   🔍  Search code with regex and glob patterns                         │
│   🤖  Spawn sub-agents for parallel work                               │
│   🌐  Fetch web content and search the internet                        │
│   🔌  Connect to external tools via MCP (Model Context Protocol)       │
│   📋  Manage tasks, todos, and session state                           │
│   🎨  Provide beautiful terminal UI with themes                        │
│                                                                        │
└────────────────────────────────────────────────────────────────────────┘
```

### Available Platforms

| Platform | Status | Description |
|----------|--------|-------------|
| 🖥️ **CLI** | ✅ Primary | `claude` command in terminal |
| 💻 **VS Code** | ✅ Available | Extension for VS Code |
| 🔧 **JetBrains** | ✅ Available | Plugin for IntelliJ-based IDEs |
| 🌐 **Web** | ✅ Available | claude.ai/code |
| 🍎 **Desktop** | ✅ Available | Mac & Windows apps |

---

## 🔓 How It Leaked

```mermaid
flowchart LR
    subgraph Anthropic["🏢 Anthropic"]
        A[("📦 npm publish\nv2.1.88")]
        B[("🗺️ Source Map\n.map file")]
    end
    
    subgraph NPM["📦 npm Registry"]
        C[("Bundle +\nSource Map\n59.8 MB")]
    end
    
    subgraph Community["🌍 Community"]
        D[("🔍 Discovery")]
        E[("📂 Extraction")]
        F[("🔄 Mirrors")]
    end
    
    A --> |"Accidentally\nincluded"| B
    B --> C
    C --> |"Downloaded by\ndevelopers"| D
    D --> E
    E --> |"GitHub repos\ncreated"| F
    
    style A fill:#ff6b6b,color:#fff
    style B fill:#ff6b6b,color:#fff
    style F fill:#4ecdc4,color:#fff
```

**Timeline:**
- **March 31, 2026** — Source map accidentally bundled in npm package v2.1.88
- **Within hours** — Community discovers and extracts 512K+ lines of TypeScript
- **Same day** — Multiple GitHub mirrors created before DMCA takedowns
- **Ongoing** — Anthropic issues takedown requests; mirrors persist

---

## 🏗 Architecture

### High-Level System Design

```mermaid
graph TB
    subgraph UI["👤 User Interfaces"]
        CLI["🖥️ CLI<br/><i>Terminal</i>"]
        VSC["💻 VS Code<br/><i>Extension</i>"]
        JB["🔧 JetBrains<br/><i>Plugin</i>"]
        WEB["🌐 Web<br/><i>claude.ai/code</i>"]
        DESK["🖥️ Desktop<br/><i>Mac/Windows</i>"]
    end
    
    subgraph Bridge["🌉 Transport Layer"]
        WS["WebSocket"]
        SSE["Server-Sent Events"]
        HYB["Hybrid Transport"]
    end
    
    subgraph Core["⚙️ Core Engine"]
        QE["🧠 QueryEngine<br/><i>46K lines</i>"]
        TS["🔧 Tool System"]
        PM["🔐 Permission Manager"]
        CM["📊 Context Manager"]
    end
    
    subgraph Tools["🛠️ Tool System"]
        direction LR
        BASH["Bash"]
        FILE["File Ops"]
        SEARCH["Search"]
        AGENT["Agent"]
        MCP["MCP"]
    end
    
    subgraph External["🌍 External Services"]
        API["☁️ Anthropic API"]
        MCPS["🔌 MCP Servers"]
        GIT["📂 Git/GitHub"]
    end
    
    CLI & VSC & JB & WEB & DESK --> Bridge
    Bridge --> Core
    Core --> Tools
    Tools --> External
    
    style QE fill:#6c5ce7,color:#fff
    style API fill:#00b894,color:#fff
```

### Request Flow

```mermaid
sequenceDiagram
    autonumber
    participant U as 👤 User
    participant UI as 🖥️ Interface
    participant B as 🌉 Bridge
    participant QE as 🧠 QueryEngine
    participant T as 🔧 Tools
    participant API as ☁️ Claude API
    
    U->>UI: Enter prompt
    UI->>B: Send message
    B->>QE: Process query
    
    loop Tool Execution
        QE->>API: Send context + tools
        API-->>QE: Response + tool calls
        QE->>T: Execute tool
        T-->>QE: Tool result
    end
    
    QE->>API: Final response
    API-->>QE: Assistant message
    QE-->>B: Stream response
    B-->>UI: Display output
    UI-->>U: Show result
```

### Tool Execution Pipeline

```mermaid
flowchart TB
    subgraph Input["📥 Input"]
        REQ["Tool Request"]
    end
    
    subgraph Validation["✅ Validation"]
        SCHEMA["Schema Check<br/><i>Zod</i>"]
        PERM["Permission Check"]
        SEC["Security Scan"]
    end
    
    subgraph Execution["⚡ Execution"]
        SANDBOX["Sandbox<br/><i>Optional</i>"]
        EXEC["Execute Tool"]
        PROG["Progress Events"]
    end
    
    subgraph Output["📤 Output"]
        RES["Tool Result"]
        ERR["Error Handler"]
    end
    
    REQ --> SCHEMA
    SCHEMA -->|Valid| PERM
    SCHEMA -->|Invalid| ERR
    PERM -->|Allowed| SEC
    PERM -->|Denied| ERR
    SEC -->|Safe| SANDBOX
    SEC -->|Dangerous| ERR
    SANDBOX --> EXEC
    EXEC --> PROG
    PROG --> RES
    
    style REQ fill:#3498db,color:#fff
    style RES fill:#27ae60,color:#fff
    style ERR fill:#e74c3c,color:#fff
```

---

## 📂 Directory Structure

```
claude-code/
│
├── 🎯 main.tsx                    # Application entry point
├── 📋 commands.ts                 # Command registry (85+ commands)
├── 🔧 Tool.ts                     # Tool base definitions
├── 🔍 query.ts                    # Query execution
├── 🧠 QueryEngine.ts              # Core LLM engine (46K lines!)
│
├── 🌉 bridge/                     # Remote session management
│   ├── bridgeMain.ts              #   Main orchestration
│   ├── replBridge.ts              #   REPL implementation
│   ├── sessionRunner.ts           #   Session execution
│   └── types.ts                   #   Type definitions
│
├── 💻 cli/                        # Command-line interface
│   ├── handlers/                  #   Command handlers
│   ├── transports/                #   SSE, WebSocket, Hybrid
│   │   ├── SSETransport.ts
│   │   ├── WebSocketTransport.ts
│   │   └── HybridTransport.ts
│   └── print.ts                   #   Output formatting
│
├── ⌨️ commands/                   # Slash commands (~85)
│   ├── commit.ts                  #   /commit
│   ├── compact/                   #   /compact
│   ├── config/                    #   /config
│   ├── doctor/                    #   /doctor
│   ├── mcp/                       #   /mcp
│   ├── plan/                      #   /plan
│   ├── review/                    #   /review
│   ├── buddy/                     #   /buddy (Easter egg!)
│   └── ...                        #   Many more...
│
├── 🎨 components/                 # React/Ink UI components
│   ├── Spinner.js
│   ├── ThemePicker.tsx
│   └── ...
│
├── 📜 constants/                  # Prompts & configuration
│   ├── prompts.ts                 #   System prompts (THE BRAIN!)
│   ├── cyberRiskInstruction.ts    #   Security guardrails
│   └── outputStyles.ts            #   Output formatting
│
├── 🪝 hooks/                      # React hooks
│   ├── useCanUseTool.ts
│   ├── toolPermission/
│   └── ...
│
├── 🧠 memdir/                     # Memory persistence
│   ├── memdir.ts
│   ├── memoryTypes.ts
│   └── findRelevantMemories.ts
│
├── ⚙️ services/                   # Core services
│   ├── analytics/                 #   Telemetry (GrowthBook, DataDog)
│   ├── api/                       #   Claude API client
│   ├── compact/                   #   Context compaction
│   ├── mcp/                       #   Model Context Protocol
│   ├── oauth/                     #   Authentication
│   └── plugins/                   #   Plugin management
│
├── 🎯 skills/                     # Skills system
│   ├── bundled/                   #   Built-in skills
│   │   ├── debug.ts
│   │   ├── verify.ts
│   │   ├── simplify.ts
│   │   └── ...
│   └── loadSkillsDir.ts
│
├── 🛠️ tools/                      # Agent tools (~40)
│   ├── BashTool/                  #   Shell execution
│   ├── FileReadTool/              #   Read files
│   ├── FileEditTool/              #   Edit files
│   ├── FileWriteTool/             #   Create files
│   ├── GrepTool/                  #   Content search
│   ├── GlobTool/                  #   File patterns
│   ├── AgentTool/                 #   Sub-agents
│   ├── WebFetchTool/              #   Fetch URLs
│   ├── WebSearchTool/             #   Web search
│   ├── MCPTool/                   #   MCP integration
│   └── ...
│
├── 🔧 utils/                      # Utilities
│   ├── bash/                      #   Bash parsing
│   ├── permissions/               #   Permission system
│   ├── sandbox/                   #   Sandbox execution
│   └── ...
│
└── ⌨️ vim/                        # Vim keybindings
    ├── motions.ts
    ├── operators.ts
    └── textObjects.ts
```

---

## 🧠 Core Engine

### QueryEngine — The Brain

The `QueryEngine.ts` is the heart of Claude Code with **46,000+ lines** handling:

```mermaid
mindmap
  root((QueryEngine))
    API Communication
      Streaming responses
      Token counting
      Error recovery
      Retry logic
    Tool Orchestration
      Tool selection
      Parallel execution
      Result aggregation
      Permission checks
    Context Management
      Window tracking
      Auto-compaction
      Memory persistence
      History snipping
    State Management
      Session tracking
      Progress updates
      Budget enforcement
      Cancellation
```

### System Prompts — The Personality

Located in `constants/prompts.ts`, this defines Claude Code's behavior:

```typescript
// Key sections in the system prompt:
├── Identity & Capabilities
├── Tool Usage Guidelines
├── Code Style Preferences
├── Security Constraints
├── Output Formatting Rules
├── Language Preferences
├── MCP Instructions
└── Autonomous Mode Rules
```

---

## 🛠 Tools

Claude Code provides **40+ tools** organized by category:

### Complete Tool Map

```mermaid
graph TB
    subgraph FileOps["📁 File Operations"]
        FR["FileReadTool<br/><i>Read files</i>"]
        FW["FileWriteTool<br/><i>Create files</i>"]
        FE["FileEditTool<br/><i>Edit files</i>"]
        NE["NotebookEditTool<br/><i>Jupyter</i>"]
    end
    
    subgraph Search["🔍 Search & Navigation"]
        GL["GlobTool<br/><i>Find files</i>"]
        GR["GrepTool<br/><i>Search content</i>"]
        LS["LSPTool<br/><i>Language Server</i>"]
    end
    
    subgraph Exec["⚡ Execution"]
        BA["BashTool<br/><i>Shell commands</i>"]
        PS["PowerShellTool<br/><i>Windows</i>"]
        AG["AgentTool<br/><i>Sub-agents</i>"]
    end
    
    subgraph Web["🌐 Web & External"]
        WF["WebFetchTool<br/><i>Fetch URLs</i>"]
        WS["WebSearchTool<br/><i>Search web</i>"]
        MC["MCPTool<br/><i>MCP calls</i>"]
        RM["ReadMcpResource"]
        LM["ListMcpResources"]
    end
    
    subgraph Tasks["📋 Task Management"]
        TW["TodoWriteTool"]
        TC["TaskCreateTool"]
        TG["TaskGetTool"]
        TL["TaskListTool"]
        TU["TaskUpdateTool"]
        TS["TaskStopTool"]
    end
    
    subgraph Comm["💬 Communication"]
        AQ["AskUserQuestion"]
        SM["SendMessageTool"]
    end
    
    subgraph Mode["🔄 Mode Switching"]
        EP["EnterPlanMode"]
        XP["ExitPlanMode"]
        EW["EnterWorktree"]
        XW["ExitWorktree"]
    end
    
    subgraph Auto["⏰ Automation"]
        SC["ScheduleCronTool"]
        SL["SleepTool"]
        RT["RemoteTriggerTool"]
    end
    
    style FileOps fill:#3498db,color:#fff
    style Search fill:#9b59b6,color:#fff
    style Exec fill:#e74c3c,color:#fff
    style Web fill:#1abc9c,color:#fff
    style Tasks fill:#f39c12,color:#fff
    style Comm fill:#2ecc71,color:#fff
    style Mode fill:#34495e,color:#fff
    style Auto fill:#e91e63,color:#fff
```

### Tool Details

<details>
<summary><b>📁 File Operations</b></summary>

| Tool | Description | Key Features |
|------|-------------|--------------|
| `FileReadTool` | Read file contents | Line numbers, encoding detection |
| `FileWriteTool` | Create new files | Atomic writes, backup |
| `FileEditTool` | Edit existing files | Search/replace, multi-edit |
| `NotebookEditTool` | Edit Jupyter notebooks | Cell-level editing |

</details>

<details>
<summary><b>🔍 Search & Navigation</b></summary>

| Tool | Description | Key Features |
|------|-------------|--------------|
| `GlobTool` | Find files by pattern | Recursive, exclusions |
| `GrepTool` | Search file contents | Regex, context lines |
| `LSPTool` | Language Server Protocol | Go-to-definition, hover |

</details>

<details>
<summary><b>⚡ Execution</b></summary>

| Tool | Description | Key Features |
|------|-------------|--------------|
| `BashTool` | Execute shell commands | Timeout, sandbox, streaming |
| `PowerShellTool` | Windows PowerShell | Cross-platform |
| `AgentTool` | Spawn sub-agents | Parallel work, fork mode |

</details>

<details>
<summary><b>🌐 Web & External</b></summary>

| Tool | Description | Key Features |
|------|-------------|--------------|
| `WebFetchTool` | Fetch URL contents | Markdown conversion |
| `WebSearchTool` | Search the web | Multiple providers |
| `MCPTool` | Call MCP tools | Dynamic discovery |
| `ReadMcpResourceTool` | Read MCP resources | URI-based |
| `ListMcpResourcesTool` | List MCP resources | Discovery |

</details>

---

## ⌨️ Commands

### Command Distribution

```mermaid
pie title Slash Commands by Category
    "Session Management" : 12
    "Git & Version Control" : 10
    "Configuration" : 15
    "Development" : 18
    "Information" : 8
    "Mode Switching" : 6
    "Utilities" : 10
    "Hidden/Internal" : 6
```

### Complete Command Reference

<details>
<summary><b>📂 Session Management</b></summary>

```bash
/session        # Manage sessions
/resume         # Resume previous session
/clear          # Clear conversation
/compact        # Compact context window
/exit           # Exit Claude Code
/export         # Export session
/share          # Share session link
```

</details>

<details>
<summary><b>🔀 Git & Version Control</b></summary>

```bash
/commit         # Create git commit
/commit-push-pr # Commit, push, and create PR
/branch         # Manage branches
/pr_comments    # View PR comments
/diff           # Show diffs
/review         # Code review
```

</details>

<details>
<summary><b>⚙️ Configuration</b></summary>

```bash
/config         # Edit configuration
/permissions    # Manage permissions
/hooks          # Configure hooks
/theme          # Change theme
/vim            # Toggle vim mode
/keybindings    # Configure keybindings
/model          # Switch models
/output-style   # Change output style
```

</details>

<details>
<summary><b>🛠️ Development</b></summary>

```bash
/doctor         # Run diagnostics
/init           # Initialize project
/mcp            # Manage MCP servers
/plugin         # Manage plugins
/skills         # List available skills
/agents         # List available agents
```

</details>

<details>
<summary><b>📊 Information</b></summary>

```bash
/help           # Show help
/cost           # Show usage costs
/usage          # Show API usage
/stats          # Show statistics
/insights       # Generate session report
/version        # Show version
```

</details>

<details>
<summary><b>🔀 Mode Switching</b></summary>

```bash
/plan           # Enter planning mode
/fast           # Toggle fast mode
/voice          # Toggle voice mode
/assistant      # Assistant mode (hidden)
/proactive      # Autonomous mode (hidden)
```

</details>

<details>
<summary><b>🎁 Hidden Commands</b></summary>

```bash
/buddy          # 🐾 Digital pet system!
/dream          # Dream mode (KAIROS)
/torch          # Unknown feature
/ultraplan      # Advanced planning
/ultrareview    # Advanced review
/stickers       # Sticker system
```

</details>

---

## 🚩 Feature Flags

Claude Code uses **44+ feature flags** for gradual rollouts:

### Flag Categories

```mermaid
graph LR
    subgraph Core["🎯 Core Features"]
        K["KAIROS<br/><i>Autonomous mode</i>"]
        P["PROACTIVE<br/><i>Background help</i>"]
        B["BRIDGE_MODE<br/><i>Remote sessions</i>"]
        V["VOICE_MODE<br/><i>Voice I/O</i>"]
        D["DAEMON<br/><i>Background daemon</i>"]
    end
    
    subgraph Exp["🧪 Experimental"]
        BU["BUDDY<br/><i>Digital pet 🐾</i>"]
        TO["TORCH<br/><i>Unknown</i>"]
        UP["ULTRAPLAN<br/><i>Adv. planning</i>"]
        FS["FORK_SUBAGENT<br/><i>Fork agents</i>"]
        SS["SKILL_SEARCH<br/><i>Discovery</i>"]
    end
    
    subgraph Ctx["📊 Context"]
        CM["CACHED_MICROCOMPACT"]
        CC["CONTEXT_COLLAPSE"]
        RC["REACTIVE_COMPACT"]
        HS["HISTORY_SNIP"]
        TB["TOKEN_BUDGET"]
    end
    
    subgraph Int["🔗 Integration"]
        GH["GITHUB_WEBHOOKS"]
        KC["KAIROS_CHANNELS"]
        MS["MCP_SKILLS"]
        BA["BUILDING_CLAUDE_APPS"]
    end
    
    style K fill:#e74c3c,color:#fff
    style BU fill:#f1c40f,color:#000
    style CM fill:#3498db,color:#fff
    style GH fill:#2ecc71,color:#fff
```

### Complete Flag Reference

| Flag | Category | Description |
|------|----------|-------------|
| `KAIROS` | Core | Autonomous agent mode |
| `PROACTIVE` | Core | Proactive assistance |
| `BRIDGE_MODE` | Core | Remote bridge functionality |
| `VOICE_MODE` | Core | Voice input/output |
| `DAEMON` | Core | Background daemon mode |
| `BUDDY` | Experimental | 🐾 Digital pet system |
| `TORCH` | Experimental | Unknown advanced feature |
| `ULTRAPLAN` | Experimental | Advanced planning mode |
| `FORK_SUBAGENT` | Experimental | Fork-based subagents |
| `EXPERIMENTAL_SKILL_SEARCH` | Experimental | Skill discovery |
| `CACHED_MICROCOMPACT` | Context | Cached context compaction |
| `CONTEXT_COLLAPSE` | Context | Context collapsing |
| `REACTIVE_COMPACT` | Context | Reactive compaction |
| `HISTORY_SNIP` | Context | History trimming |
| `TOKEN_BUDGET` | Context | Token budget tracking |
| `KAIROS_GITHUB_WEBHOOKS` | Integration | GitHub webhooks |
| `KAIROS_CHANNELS` | Integration | Channel communication |
| `MCP_SKILLS` | Integration | MCP-based skills |
| `BUILDING_CLAUDE_APPS` | Integration | Claude API assistance |
| `BASH_CLASSIFIER` | Internal | Command classification |
| `TRANSCRIPT_CLASSIFIER` | Internal | Transcript analysis |
| `VERIFICATION_AGENT` | Internal | Verification subagent |
| `REVIEW_ARTIFACT` | Internal | Review artifacts |

---

## 🎯 Skills System

### How Skills Work

```mermaid
flowchart LR
    subgraph Discovery["🔍 Discovery"]
        BD["Bundled Skills<br/><i>skills/bundled/</i>"]
        GS["Global Skills<br/><i>~/.claude/skills/</i>"]
        PS["Project Skills<br/><i>.claude/skills/</i>"]
        MS["MCP Skills<br/><i>Dynamic</i>"]
    end
    
    subgraph Loading["📦 Loading"]
        LD["loadSkillsDir.ts"]
        BK["bundledSkills.ts"]
    end
    
    subgraph Invocation["⚡ Invocation"]
        SL["Slash Command<br/><i>/skillname</i>"]
        ST["SkillTool"]
    end
    
    subgraph Execution["🎯 Execution"]
        PR["Prompt Expansion"]
        EX["Execute"]
    end
    
    BD & GS & PS & MS --> LD & BK
    LD & BK --> SL
    SL --> ST
    ST --> PR
    PR --> EX
```

### Bundled Skills

```typescript
skills/bundled/
├── 🐛 debug.ts           // /debug - Debugging assistance
├── ✅ verify.ts          // /verify - Verification
├── 🎯 simplify.ts        // /simplify - Code simplification
├── 💾 remember.ts        // /remember - Memory management
├── ⌨️ keybindings.ts     // /keybindings - Keybinding help
├── 🆘 stuck.ts           // /stuck - Help when stuck
├── 📦 batch.ts           // /batch - Batch operations
├── ✨ skillify.ts        // /skillify - Create new skills
├── 📝 loremIpsum.ts      // /loremIpsum - Placeholder text
├── ⚙️ updateConfig.ts    // /updateConfig - Config updates
├── 🔌 claudeApi.ts       // Claude API help (gated)
├── 🌐 claudeInChrome.ts  // Chrome integration
├── 🔄 loop.ts            // /loop - Looping (gated)
├── 💭 dream.ts           // /dream - Dream mode (gated)
└── 🔍 hunter.ts          // /hunter - Bug hunting (gated)
```

### Custom Skill Format

```markdown
---
name: my-custom-skill
description: What this skill does
---

# My Custom Skill

Instructions for Claude when this skill is invoked...

## Steps
1. First, do this
2. Then, do that
3. Finally, complete the task
```

---

## 🔌 MCP Integration

### Model Context Protocol Architecture

```mermaid
flowchart TB
    subgraph ClaudeCode["🤖 Claude Code"]
        MC["MCP Client<br/><i>services/mcp/client.ts</i>"]
        EL["Elicitation Handler"]
        AU["OAuth/Auth"]
    end
    
    subgraph Protocol["📡 MCP Protocol"]
        TOOLS["🔧 Tools"]
        RES["📚 Resources"]
        PROM["💬 Prompts"]
    end
    
    subgraph Servers["🌐 MCP Servers"]
        OFF["Official Registry"]
        CUST["Custom Servers"]
        SDK["VS Code SDK"]
    end
    
    MC --> TOOLS & RES & PROM
    AU --> Servers
    EL --> |"User Confirmation"| Servers
    TOOLS & RES & PROM --> Servers
    
    style MC fill:#6c5ce7,color:#fff
    style OFF fill:#00b894,color:#fff
```

### MCP Services

```
services/mcp/
├── 🔌 client.ts              # MCP client implementation
├── ⚙️ config.ts              # Configuration
├── 📦 types.ts               # Type definitions
├── 🔐 auth.ts                # OAuth for MCP servers
├── ☁️ claudeai.ts            # Claude.ai integration
├── 💻 vscodeSdkMcp.ts        # VS Code SDK
├── 🔒 channelAllowlist.ts    # Channel permissions
├── ❓ elicitationHandler.ts  # User prompting
├── 📋 officialRegistry.ts    # Official servers
└── 🛠️ utils.ts               # Utilities
```

---

## 🔐 Security

### Security Architecture

```mermaid
flowchart TB
    subgraph Input["📥 User Input"]
        CMD["Command/Prompt"]
    end
    
    subgraph Analysis["🔍 Security Analysis"]
        AST["Bash AST Parser<br/><i>utils/bash/ast.ts</i>"]
        SEC["Secret Scanner<br/><i>secretScanner.ts</i>"]
        CYB["Cyber Risk Check<br/><i>cyberRiskInstruction.ts</i>"]
    end
    
    subgraph Permission["🔐 Permission System"]
        PM["Permission Mode<br/><i>default/auto/plan</i>"]
        PT["Per-Tool Rules"]
        FA["File Access Control"]
    end
    
    subgraph Execution["⚡ Execution"]
        SB["Sandbox<br/><i>SandboxManager</i>"]
        EX["Execute"]
    end
    
    subgraph Safety["🛡️ Safety"]
        WARN["Destructive Warnings"]
        DENY["Denial Tracking"]
    end
    
    CMD --> Analysis
    Analysis --> Permission
    Permission -->|"Approved"| Execution
    Permission -->|"Denied"| Safety
    Execution --> SB
    SB --> EX
    
    style AST fill:#e74c3c,color:#fff
    style SB fill:#27ae60,color:#fff
```

### Cyber Risk Instruction

The security guardrail in `constants/cyberRiskInstruction.ts`:

```typescript
export const CYBER_RISK_INSTRUCTION = `
IMPORTANT: Assist with authorized security testing, 
defensive security, CTF challenges, and educational 
contexts. 

REFUSE requests for:
❌ Destructive techniques
❌ DoS attacks  
❌ Mass targeting
❌ Supply chain compromise
❌ Detection evasion for malicious purposes
`
```

### Permission Modes

| Mode | Description | Risk Level |
|------|-------------|------------|
| `default` | Ask for each action | 🟢 Low |
| `plan-mode` | Read-only operations | 🟢 Low |
| `auto-approve` | Auto-approve safe actions | 🟡 Medium |

---

## 🎁 Easter Eggs

### 🐾 BUDDY — Digital Pet System

A hidden feature gated behind `feature('BUDDY')`:

```typescript
const buddy = feature('BUDDY')
  ? require('./commands/buddy/index.js').default
  : null
```

The BUDDY system appears to be a **digital pet/companion** feature — your coding buddy that lives inside Claude Code!

### 🎨 Stickers

```bash
/stickers  # Sticker-related functionality
```

### 💭 Dream Mode

```bash
/dream  # Available when KAIROS or KAIROS_DREAM flags are enabled
```

---

## 🤖 Model Information

### Supported Models

```mermaid
graph LR
    subgraph Opus["🎭 Opus Tier"]
        O46["Claude Opus 4.6<br/><i>claude-opus-4-6</i>"]
        O45["Claude Opus 4.5"]
        O4["Claude Opus 4"]
    end
    
    subgraph Sonnet["🎵 Sonnet Tier"]
        S46["Claude Sonnet 4.6<br/><i>claude-sonnet-4-6</i>"]
        S4["Claude Sonnet 4"]
    end
    
    subgraph Haiku["🌸 Haiku Tier"]
        H45["Claude Haiku 4.5<br/><i>claude-haiku-4-5</i>"]
    end
    
    style O46 fill:#6c5ce7,color:#fff
    style S46 fill:#00b894,color:#fff
    style H45 fill:#fd79a8,color:#fff
```

### Knowledge Cutoffs

| Model | Cutoff Date |
|-------|-------------|
| Claude Opus 4.6 | **May 2025** |
| Claude Sonnet 4.6 | **August 2025** |
| Claude Opus 4.5 | May 2025 |
| Claude Haiku 4.x | February 2025 |
| Claude Opus 4 / Sonnet 4 | January 2025 |

### Fast Mode

> **Note:** Fast mode uses the **same frontier model** (Opus 4.6) with optimized output generation — it does NOT switch to a different model!

---

## 🛠️ Tech Stack

```mermaid
graph TB
    subgraph Runtime["⚡ Runtime"]
        BUN["Bun<br/><i>Fast JS Runtime</i>"]
    end
    
    subgraph Language["📝 Language"]
        TS["TypeScript"]
    end
    
    subgraph UI["🎨 UI Framework"]
        REACT["React"]
        INK["Ink<br/><i>React for CLI</i>"]
    end
    
    subgraph Validation["✅ Validation"]
        ZOD["Zod<br/><i>Schema Validation</i>"]
    end
    
    subgraph API["☁️ API"]
        ASDK["@anthropic-ai/sdk"]
        MSDK["@modelcontextprotocol/sdk"]
    end
    
    subgraph Analytics["📊 Analytics"]
        GB["GrowthBook<br/><i>Feature Flags</i>"]
        DD["DataDog<br/><i>Monitoring</i>"]
    end
    
    BUN --> TS
    TS --> REACT & INK
    TS --> ZOD
    TS --> ASDK & MSDK
    TS --> GB & DD
    
    style BUN fill:#fbbd23,color:#000
    style TS fill:#3178c6,color:#fff
    style REACT fill:#61dafb,color:#000
```

### Key Dependencies

| Package | Purpose |
|---------|---------|
| `bun` | JavaScript runtime & bundler |
| `@anthropic-ai/sdk` | Anthropic API client |
| `@modelcontextprotocol/sdk` | MCP implementation |
| `zod` | Schema validation |
| `ink` | React for terminals |
| `lodash-es` | Utility functions |

---

## 🔤 Internal Codenames

| Codename | Meaning |
|----------|---------|
| `ant` | Anthropic internal user type |
| `Kairos` | Autonomous agent mode |
| `Proactive` | Background agent assistance |
| `Bridge` | Remote session management |
| `CCR` | Claude Code Remote |
| `FRC` | Function Result Clearing |
| `Undercover` | Mode that hides model names (for unannounced models) |
| `Tengu` | Verification agent codename |
| `Chicago MCP` | Unknown MCP integration |
| `Grove` | Unknown service integration |
| `Buddy` | Digital pet feature |
| `Torch` | Unknown experimental feature |

---

## 📚 References

| Resource | Link |
|----------|------|
| 📰 Original Leak Report | [dev.to Article](https://dev.to/evan-dong/claude-codes-entire-source-code-just-leaked-512000-lines-exposed-3139) |
| 📰 Decrypt Coverage | [Decrypt Article](https://decrypt.co/362917/anthropic-accidentally-leaked-claude-code-source-internet-keeping-forever) |
| 🏢 Official Repository | [anthropics/claude-code](https://github.com/anthropics/claude-code) |
| 🔍 Deobfuscation Project | [ghuntley/claude-code-source-code-deobfuscation](https://github.com/ghuntley/claude-code-source-code-deobfuscation) |

---

<div align="center">

## 📜 License & Legal

This source code is **proprietary** and owned by **Anthropic**.

This repository is maintained **strictly for educational and research purposes**.

All rights reserved by Anthropic.

---

<sub>Last updated: March 2026 • This is an archival repository</sub>

</div>
