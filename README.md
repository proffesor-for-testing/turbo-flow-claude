# 🚀 Turbo Flow Claude v3.4.0

<div align="center">

![Version](https://img.shields.io/badge/version-3.4.0-blue?style=for-the-badge)
![Claude Flow](https://img.shields.io/badge/Claude_Flow-V3-purple?style=for-the-badge)
![RuVector](https://img.shields.io/badge/RuVector-Neural_Engine-green?style=for-the-badge)
![Skills](https://img.shields.io/badge/Skills-56_Total-orange?style=for-the-badge)
![Plugins](https://img.shields.io/badge/Plugins-15-critical?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)

**⚡ Complete Agentic Development Environment — Claude Flow V3 + RuVector + All Plugins ⚡**

[Quick Start](#-quick-start) • [Installation](#-what-gets-installed) • [Skills](#-skills-41-total) • [Plugins](#-plugins-15-total) • [Commands](#️-key-commands) • [Resources](#-resources)

</div>

---

## 🆕 What's New in v3.4.0

| Metric | v3.3.0 | v3.4.0 | Change |
|--------|--------|--------|--------|
| Native Skills | 36 | **36** | — |
| Plugins | 0 | **15** | +15 ⭐ |
| Custom Skills | 5 | **5** | — |
| **Total Components** | **41** | **56** | +37% |
| Bash Aliases | 50+ | **70+** | +40% |
| Installation Steps | 18 | **19** | +1 |

### Major Additions in v3.4.0

- ✅ **15 Claude Flow Plugins** — Complete plugin coverage for domain-specific workflows
- ✅ **Plugin Aliases** — Quick commands for all plugins
- ✅ **70+ Bash Aliases** — Extended with plugin-specific shortcuts

### From v3.3.0

- ✅ **36 Native Claude Flow Skills** — Complete coverage of all available skills
- ✅ **Memory System** — HNSW vector search, AgentDB, LearningBridge
- ✅ **MCP Server Registration** — 175+ tools auto-registered
- ✅ **Cyberpunk Statusline** — 15-component, 3-line status display
- ✅ **Enhanced Verification** — post-setup.sh checks 100+ items

---

## 🏗️ Architecture

```
╔══════════════════════════════════════════════════════════════════════╗
║                       🚀 TURBO FLOW v3.4.0                           ║
╠══════════════════════════════════════════════════════════════════════╣
║  🖥️  INTERFACE                                                        ║
║  ┌──────────────┐ ┌──────────────┐ ┌──────────────┐                  ║
║  │ Claude Code  │ │ Agent Browser│ │  Statusline  │                  ║
║  │     CLI      │ │  Automation  │ │   Pro (15)   │                  ║
║  └──────────────┘ └──────────────┘ └──────────────┘                  ║
╠══════════════════════════════════════════════════════════════════════╣
║  🧠 NEURAL ENGINE: RuVector                                          ║
║  ┌────────┐ ┌────────┐ ┌────────┐ ┌────────┐ ┌────────┐             ║
║  │  SONA  │ │  HNSW  │ │  MoE   │ │ EWC++  │ │  GNN   │             ║
║  │<0.05ms │ │  150x  │ │8 expert│ │95% keep│ │ layers │             ║
║  └────────┘ └────────┘ └────────┘ └────────┘ └────────┘             ║
╠══════════════════════════════════════════════════════════════════════╣
║  🎯 ORCHESTRATION: Claude Flow V3                                    ║
║  60+ Agents  │  175+ MCP Tools  │  Background Workers                ║
╠══════════════════════════════════════════════════════════════════════╣
║  📚 SKILLS (41 Total)                                                ║
║  ┌─────────────────────────────────────────────────────────────────┐ ║
║  │ Core(6) │ AgentDB(4) │ GitHub(4) │ V3Dev(9) │ Reasoning(2)    │ ║
║  │ FlowNexus(3) │ Additional(8) │ Custom(5)                       │ ║
║  └─────────────────────────────────────────────────────────────────┘ ║
╠══════════════════════════════════════════════════════════════════════╣
║  🔌 PLUGINS (15 Total) ⭐ NEW                                        ║
║  ┌─────────────────────────────────────────────────────────────────┐ ║
║  │ QE(2) │ CodeIntel(1) │ Cognitive(2) │ Perf(3) │ Neural(2)     │ ║
║  │ Domain(3) │ WASM(1) │ Upstream(1)                                │ ║
║  └─────────────────────────────────────────────────────────────────┘ ║
╠══════════════════════════════════════════════════════════════════════╣
║  💾 MEMORY SYSTEM                                                    ║
║  HNSW Vector Search │ AgentDB SQLite │ LearningBridge │ 3-Scope    ║
╠══════════════════════════════════════════════════════════════════════╣
║  🧪 TESTING          │  🔒 SECURITY        │  📋 SPECS               ║
║  Agentic QE          │  Security Analyzer  │  Spec-Kit               ║
║  Verification(0.95)  │  Codex (optional)   │  OpenSpec               ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

## 🏁 Quick Start

### 📦 DevPod Installation

<details>
<summary><b>macOS</b></summary>

```bash
brew install loft-sh/devpod/devpod
```
</details>

<details>
<summary><b>Windows</b></summary>

```bash
choco install devpod
```
</details>

<details>
<summary><b>Linux</b></summary>

```bash
curl -L -o devpod "https://github.com/loft-sh/devpod/releases/latest/download/devpod-linux-amd64"
sudo install devpod /usr/local/bin
```
</details>

### 🚀 Launch

```bash
devpod up https://github.com/marcuspat/turbo-flow-claude --ide vscode
```

---

## 📦 What Gets Installed

The `setup.sh` script installs the complete stack in **19 automated steps**:

### Step 1️⃣ Build Tools

| Package | Purpose |
|:--------|:--------|
| `build-essential` | C/C++ compiler (gcc, g++, make) |
| `python3` | Python runtime |
| `git` | Version control |
| `curl` | HTTP client |
| `jq` | JSON processor (required for statusline) |

---

### Step 2️⃣ Claude Flow V3 + RuVector

> 🔄 **Delegated to official installer** — handles everything automatically

| Component | Purpose |
|:----------|:--------|
| ![Node](https://img.shields.io/badge/Node.js-20+-339933?logo=node.js&logoColor=white) | JavaScript runtime |
| ![Claude](https://img.shields.io/badge/Claude_Code-CLI-8B5CF6?logo=anthropic&logoColor=white) | AI coding assistant |
| `claude-flow@alpha` | 60+ agents, 175+ MCP tools |
| `ruvector` | Vector DB + GNN + self-learning |
| `@ruvector/cli` | Hooks & intelligence |
| `@ruvector/sona` | Self-Optimizing Neural Architecture |

---

### Steps 3️⃣-🔟 Native Claude Flow Skills (36)

#### Core Skills (6)

| Skill | Purpose |
|:------|:--------|
| `sparc-methodology` | SPARC development methodology |
| `swarm-orchestration` | Multi-agent coordination (mesh/hierarchical) |
| `github-code-review` | AI-powered PR reviews |
| `agentdb-vector-search` | HNSW vector search (150x faster) |
| `pair-programming` | Driver/Navigator AI coding |
| `hive-mind-advanced` | Queen-led collective intelligence |

#### AgentDB Skills (4)

| Skill | Purpose |
|:------|:--------|
| `agentdb-advanced` | QUIC sync, multi-database, custom metrics |
| `agentdb-learning` | 9 RL algorithms (Q-Learning, Actor-Critic) |
| `agentdb-memory-patterns` | Session memory, pattern learning |
| `agentdb-optimization` | Quantization (4-32x memory reduction) |

#### GitHub Skills (4)

| Skill | Purpose |
|:------|:--------|
| `github-multi-repo` | Cross-repository coordination |
| `github-project-management` | Issues, project boards, sprints |
| `github-release-management` | Versioning, deployment, rollback |
| `github-workflow-automation` | CI/CD pipeline automation |

#### V3 Development Skills (9)

| Skill | Purpose |
|:------|:--------|
| `v3-cli-modernization` | Interactive prompts, command decomposition |
| `v3-core-implementation` | DDD domains, clean architecture |
| `v3-ddd-architecture` | Bounded contexts, microkernel |
| `v3-integration-deep` | Deep agentic-flow integration |
| `v3-mcp-optimization` | Sub-100ms MCP response |
| `v3-memory-unification` | Unified AgentDB backend |
| `v3-performance-optimization` | Flash Attention (2.49x-7.47x) |
| `v3-security-overhaul` | CVE remediation |
| `v3-swarm-coordination` | 15-agent hierarchical mesh |

#### ReasoningBank Skills (2)

| Skill | Purpose |
|:------|:--------|
| `reasoningbank-agentdb` | Trajectory tracking, memory distillation |
| `reasoningbank-intelligence` | Pattern recognition, meta-cognition |

#### Flow Nexus Skills (3)

| Skill | Purpose |
|:------|:--------|
| `flow-nexus-neural` | Neural network training in E2B sandboxes |
| `flow-nexus-platform` | Auth, sandboxes, app deployment |
| `flow-nexus-swarm` | Cloud-based swarm deployment |

#### Additional Skills (8)

| Skill | Purpose |
|:------|:--------|
| `agentic-jujutsu` | Quantum-resistant version control |
| `hooks-automation` | Pre/post task hooks, neural training |
| `performance-analysis` | Bottleneck detection, profiling |
| `skill-builder` | Create custom Claude Code skills |
| `stream-chain` | Multi-agent streaming pipelines |
| `swarm-advanced` | Advanced distributed workflows |
| `verification-quality` | Truth scoring (0.95), automatic rollback |
| `dual-mode` | Dual-mode operations |

---

### Step 1️⃣1️⃣ Claude Flow Plugins (15) ⭐ NEW

#### Quality Engineering Plugins (2)

| Plugin | Purpose |
|:-------|:--------|
| `agentic-qe` | Autonomous quality engineering, test generation |
| `test-intelligence` | Smart test selection, coverage optimization |

#### Code Intelligence Plugins (1)

| Plugin | Purpose |
|:-------|:--------|
| `code-intelligence` | AST analysis, code understanding, refactoring |

#### Cognitive Plugins (2)

| Plugin | Purpose |
|:-------|:--------|
| `cognitive-kernel` | Meta-cognition, self-reflection, reasoning |
| `hyperbolic-reasoning` | Hyperbolic geometry for complex reasoning |

#### Performance Plugins (3)

| Plugin | Purpose |
|:-------|:--------|
| `perf-optimizer` | Performance profiling, optimization suggestions |
| `quantum-optimizer` | Quantum-inspired optimization algorithms |
| `prime-radiant` | Predictive performance modeling |

#### Neural Plugins (2)

| Plugin | Purpose |
|:-------|:--------|
| `neural-coordination` | Multi-agent neural coordination |
| `ruvector-upstream` | Direct RuVector integration |

#### Domain-Specific Plugins (3)

| Plugin | Purpose |
|:-------|:--------|
| `financial-risk` | Financial modeling, risk assessment |
| `healthcare-clinical` | Clinical workflows, medical terminology |
| `legal-contracts` | Contract analysis, legal document processing |

#### Infrastructure Plugins (2)

| Plugin | Purpose |
|:-------|:--------|
| `gastown-bridge` | WASM bridge for high-performance computing |
| `teammate-plugin` | Team collaboration, role assignment |

---

### Step 1️⃣2️⃣ Memory System

| Component | Performance |
|:----------|:------------|
| **HNSW Vector Search** | 150x-12,500x faster than standard |
| **AgentDB** | SQLite-based with WAL mode, <100µs search |
| **LearningBridge** | Bidirectional sync with Claude Code |
| **3-Scope Memory** | Project/local/user scoping |

---

### Step 1️⃣3️⃣ MCP Server Registration

Automatic registration of Claude Flow MCP server:

| Tool Category | Count |
|:--------------|:------|
| Agent tools | 20+ |
| Memory tools | 15+ |
| Swarm tools | 10+ |
| GitHub tools | 10+ |
| Browser tools | 59 |
| **Total** | **175+** |

---

### Steps 1️⃣4️⃣-1️⃣6️⃣ Custom Skills (5)

| Skill | Source | Purpose |
|:------|:-------|:--------|
| 🔒 `security-analyzer` | GitHub (Cornjebus) | Security vulnerability scanning |
| 🎨 `ui-ux-pro-max` | uipro-cli | UI/UX design assistance |
| 🌳 `worktree-manager` | GitHub (Wirasm) | Git worktree management |
| 🚀 `vercel-deploy` | Vercel Labs | One-command Vercel deployment |
| 📊 `rUv_helpers` | GitHub (Jordi-Izquierdo) | RuVector visualization |

---

### Step 1️⃣7️⃣ Statusline Pro

15-component cyberpunk statusline across 3 lines:

```
LINE 1: 📁 Project │ 🤖 Model │ 🌿 Branch │ 📟 Version │ 🎨 Style
LINE 2: 📊 Tokens │ 🧠 Context │ 💾 Cache │ 💰 Cost │ 🔥 Burn │ ⏱️ Time
LINE 3: ➕ Added │ ➖ Removed │ 📂 Git │ 🌳 Worktree │ 🔌 MCP │ ✅ Status
```

---

### Step 1️⃣8️⃣ Workspace Setup

| Component | Purpose |
|:----------|:--------|
| 📁 Directories | `src/` `tests/` `docs/` `scripts/` `config/` `plans/` |
| ⚙️ `tsconfig.json` | TypeScript (ES2022, ESNext) |
| 🎨 `@heroui/react` | UI component library |
| 🎬 `framer-motion` | Animations |
| 🌊 `tailwindcss` | Utility CSS |

---

### Step 1️⃣9️⃣ Bash Aliases (70+)

<table>
<tr>
<td>

**🧠 RuVector**
```
ruv, ruv-stats, ruv-route
ruv-remember, ruv-recall
ruv-learn, ruv-init, ruv-viz
```

</td>
<td>

**🎯 Claude Flow**
```
cf, cf-init, cf-wizard
cf-swarm, cf-mesh, cf-daemon
cf-doctor, cf-mcp, cf-memory
cf-plugin
```

</td>
</tr>
<tr>
<td>

**📚 Core Skills**
```
cf-sparc, cf-swarm-skill
cf-hive, cf-pair
cf-gh-review, cf-agentdb-search
```

</td>
<td>

**🗄️ AgentDB**
```
cf-agentdb-advanced
cf-agentdb-learning
cf-agentdb-memory
cf-agentdb-opt
```

</td>
</tr>
<tr>
<td>

**🐙 GitHub**
```
cf-gh-multi, cf-gh-project
cf-gh-release, cf-gh-workflow
```

</td>
<td>

**🔧 V3 Development**
```
cf-v3-cli, cf-v3-core
cf-v3-ddd, cf-v3-perf
cf-v3-security
```

</td>
</tr>
<tr>
<td>

**🔌 Plugins - QE**
```
plugin-qe, plugin-test-intel
```

</td>
<td>

**🔌 Plugins - Cognitive**
```
plugin-cognitive
plugin-hyperbolic
```

</td>
</tr>
<tr>
<td>

**🔌 Plugins - Perf**
```
plugin-perf, plugin-quantum
plugin-prime
```

</td>
<td>

**🔌 Plugins - Domain**
```
plugin-financial
plugin-healthcare
plugin-legal
```

</td>
</tr>
<tr>
<td>

**💾 Memory & Neural**
```
mem-search, mem-vsearch
mem-stats, neural-train
neural-patterns
```

</td>
<td>

**🌐 Browser**
```
cfb-open, cfb-snap
cfb-click, cfb-fill
cfb-trajectory, cfb-learn
```

</td>
</tr>
<tr>
<td>

**🔄 Workflow**
```
wt-status, wt-clean
wt-create, deploy
deploy-preview
```

</td>
<td>

**🧪 Testing & Quality**
```
aqe, aqe-generate, aqe-gate
cf-verify, cf-perf-analyze
```

</td>
</tr>
</table>

---

## 📚 Skills (41 Total)

### Skills by Category

| Category | Count | Skills |
|:---------|:------|:-------|
| Core | 6 | sparc, swarm, hive, pair, gh-review, agentdb-search |
| AgentDB | 4 | advanced, learning, memory-patterns, optimization |
| GitHub | 4 | multi-repo, project-mgmt, release, workflow |
| V3 Dev | 9 | cli, core, ddd, integration, mcp, memory, perf, security, swarm |
| ReasoningBank | 2 | agentdb, intelligence |
| Flow Nexus | 3 | neural, platform, swarm |
| Additional | 8 | jujutsu, hooks, perf-analysis, skill-builder, stream, swarm-adv, verify, dual |
| Custom | 5 | security-analyzer, ui-ux-pro-max, worktree-manager, vercel-deploy, rUv_helpers |

---

## 🔌 Plugins (15 Total)

### Plugins by Category

| Category | Count | Plugins |
|:---------|:------|:--------|
| Quality Engineering | 2 | agentic-qe, test-intelligence |
| Code Intelligence | 1 | code-intelligence |
| Cognitive | 2 | cognitive-kernel, hyperbolic-reasoning |
| Performance | 3 | perf-optimizer, quantum-optimizer, prime-radiant |
| Neural | 2 | neural-coordination, ruvector-upstream |
| Domain-Specific | 3 | financial-risk, healthcare-clinical, legal-contracts |
| Infrastructure | 2 | gastown-bridge, teammate-plugin |

### Plugin Quick Commands

```bash
# Quality Engineering
plugin-qe              # Run agentic-qe
plugin-test-intel      # Run test-intelligence

# Code Intelligence
plugin-code-intel      # Run code-intelligence

# Cognitive
plugin-cognitive       # Run cognitive-kernel
plugin-hyperbolic      # Run hyperbolic-reasoning

# Performance
plugin-perf            # Run perf-optimizer
plugin-quantum         # Run quantum-optimizer
plugin-prime           # Run prime-radiant

# Neural
plugin-neural          # Run neural-coordination

# Domain
plugin-financial       # Run financial-risk
plugin-healthcare      # Run healthcare-clinical
plugin-legal           # Run legal-contracts
```

---

## 📂 Directory Structure

```
📁 ~/.claude/
├── 📁 skills/
│   ├── 📚 Core (6)
│   │   ├── sparc-methodology/
│   │   ├── swarm-orchestration/
│   │   ├── github-code-review/
│   │   ├── agentdb-vector-search/
│   │   ├── pair-programming/
│   │   └── hive-mind-advanced/
│   ├── 🗄️ AgentDB (4)
│   ├── 🐙 GitHub (4)
│   ├── 🔧 V3 Dev (9)
│   ├── 🧠 ReasoningBank (2)
│   ├── ☁️ Flow Nexus (3)
│   ├── ⚡ Additional (8)
│   └── 🎨 Custom (5)
│       ├── security-analyzer/
│       ├── ui-ux-pro-max/
│       ├── worktree-manager/
│       ├── vercel-deploy/
│       └── rUv_helpers/
├── 📁 commands/
│   └── 📝 prd2build.md
├── ⚙️ settings.json
├── 📊 turbo-flow-statusline.sh
└── 📁 statusline-pro/

📁 ~/.config/claude/
└── ⚙️ mcp.json (175+ tools)

📁 ~/.codex/
└── 📄 instructions.md

📁 $WORKSPACE/
├── 📁 src/
├── 📁 tests/
├── 📁 docs/
├── 📁 scripts/
├── 📁 config/
├── 📁 plans/
├── 📁 .claude-flow/
│   ├── 📁 memory/
│   │   └── 🗄️ agent.db
│   ├── 📁 plugins/          ⭐ NEW
│   │   ├── agentic-qe/
│   │   ├── code-intelligence/
│   │   ├── cognitive-kernel/
│   │   ├── financial-risk/
│   │   ├── gastown-bridge/
│   │   ├── healthcare-clinical/
│   │   ├── hyperbolic-reasoning/
│   │   ├── legal-contracts/
│   │   ├── neural-coordination/
│   │   ├── perf-optimizer/
│   │   ├── prime-radiant/
│   │   ├── quantum-optimizer/
│   │   ├── ruvector-upstream/
│   │   ├── teammate-plugin/
│   │   └── test-intelligence/
│   └── ⚙️ config.json
├── 📁 node_modules/@heroui/
├── 🤝 AGENTS.md
├── 📦 package.json
├── ⚙️ tsconfig.json
├── 🌊 tailwind.config.js
└── 📝 .claude-flow-prompts.md
```

---

## ✅ Post-Setup

```bash
# 1️⃣ Reload shell
source ~/.bashrc

# 2️⃣ Verify installation
turbo-status

# 3️⃣ Get help
turbo-help

# 4️⃣ Run post-setup verification
./post-setup.sh

# 5️⃣ Install Codex (optional)
npm install -g @openai/codex && codex login
```

---

## ⌨️ Key Commands

<details>
<summary><b>📊 Status & Help</b></summary>

```bash
turbo-status    # Check all 56 components + 100+ items
turbo-help      # Complete command reference
cf-doctor       # Claude Flow health check
```
</details>

<details>
<summary><b>🧠 RuVector</b></summary>

```bash
ruv                  # Start RuVector
ruv-stats            # Learning statistics
ruv-route "task"     # Route to best agent
ruv-remember "ctx"   # Store in memory
ruv-recall "query"   # Search memory
ruv-viz              # Start visualization dashboard
```
</details>

<details>
<summary><b>🎯 Claude Flow V3</b></summary>

```bash
cf-init              # Initialize workspace
cf-wizard            # Interactive setup
cf-swarm             # Hierarchical swarm
cf-mesh              # Mesh swarm
cf-doctor            # Health check
cf-daemon            # Start daemon
cf-mcp               # Start MCP server
cf-memory            # Memory operations
cf-plugin            # Plugin management
```
</details>

<details>
<summary><b>📚 Core Skills</b></summary>

```bash
cf-sparc             # SPARC methodology
cf-swarm-skill       # Swarm orchestration
cf-hive              # Hive mind coordination
cf-pair              # Pair programming
cf-gh-review         # GitHub code review
cf-agentdb-search    # Vector search
```
</details>

<details>
<summary><b>🗄️ AgentDB Operations</b></summary>

```bash
cf-agentdb-advanced  # QUIC sync, multi-db
cf-agentdb-learning  # RL algorithms
cf-agentdb-memory    # Memory patterns
cf-agentdb-opt       # Optimization
```
</details>

<details>
<summary><b>🐙 GitHub Integration</b></summary>

```bash
cf-gh-multi          # Multi-repo coordination
cf-gh-project        # Project management
cf-gh-release        # Release management
cf-gh-workflow       # CI/CD automation
```
</details>

<details>
<summary><b>🔌 Plugins</b></summary>

```bash
# Quality Engineering
plugin-qe            # Agentic QE
plugin-test-intel    # Test intelligence

# Code Intelligence
plugin-code-intel    # Code understanding

# Cognitive
plugin-cognitive     # Cognitive kernel
plugin-hyperbolic    # Hyperbolic reasoning

# Performance
plugin-perf          # Performance optimizer
plugin-quantum       # Quantum optimizer
plugin-prime         # Prime radiant

# Neural
plugin-neural        # Neural coordination

# Domain-Specific
plugin-financial     # Financial risk
plugin-healthcare    # Healthcare clinical
plugin-legal         # Legal contracts
```
</details>

<details>
<summary><b>💾 Memory & Neural</b></summary>

```bash
mem-search           # Search memory
mem-vsearch          # Vector search (HNSW)
mem-vstore           # Store vector
mem-stats            # Memory statistics
neural-train         # Train neural
neural-patterns      # Neural patterns
neural-predict       # Predict
```
</details>

<details>
<summary><b>🌐 Browser Automation</b></summary>

```bash
cfb-open <url>       # Open URL via MCP
cfb-snap             # Take snapshot
cfb-click            # Click element
cfb-fill             # Fill form
cfb-trajectory       # Start trajectory learning
cfb-learn            # Save pattern
```
</details>

<details>
<summary><b>🔄 Workflow</b></summary>

```bash
wt-status            # Worktree status
wt-clean             # Cleanup worktrees
wt-create            # Create worktree
deploy               # Deploy to Vercel
deploy-preview       # Deploy with preview URL
```
</details>

<details>
<summary><b>🧪 Testing & Quality</b></summary>

```bash
aqe-generate         # Generate tests
aqe-gate             # Quality gate
cf-verify            # Truth scoring
cf-perf-analyze      # Performance analysis
```
</details>

---

## 📄 Documentation

| Document | Description |
|:---------|:------------|
| `RELEASE_NOTES_v3.4.0.md` | Full release notes |
| `Turbo_Flow_v3.4.0_Scripts_Analysis.md` | Technical analysis |
| `.claude-flow-prompts.md` | 35+ usage prompts |

---

## 🔗 Resources

| Resource | Link |
|:---------|:-----|
| 🎯 Claude Flow V3 | [![GitHub](https://img.shields.io/badge/GitHub-ruvnet/claude--flow-181717?logo=github)](https://github.com/ruvnet/claude-flow) |
| 🧠 RuVector | [![GitHub](https://img.shields.io/badge/GitHub-ruvnet/ruvector-181717?logo=github)](https://github.com/ruvnet/ruvector) |
| 🚀 Turbo Flow | [![GitHub](https://img.shields.io/badge/GitHub-marcuspat/turbo--flow--claude-181717?logo=github)](https://github.com/marcuspat/turbo-flow-claude) |
| 🧪 Agentic QE | [![npm](https://img.shields.io/badge/npm-agentic--qe-CB3837?logo=npm)](https://npmjs.com/package/agentic-qe) |
| 🎨 HeroUI | [![Website](https://img.shields.io/badge/Website-heroui.com-000000?logo=vercel)](https://heroui.com) |
| 🔒 Security Analyzer | [![GitHub](https://img.shields.io/badge/GitHub-Cornjebus/security--analyzer-181717?logo=github)](https://github.com/Cornjebus/security-analyzer) |
| 📋 Spec-Kit | [![GitHub](https://img.shields.io/badge/GitHub-github/spec--kit-181717?logo=github)](https://github.com/github/spec-kit) |

---

## 📊 Version History

| Version | Date | Changes |
|:--------|:-----|:--------|
| **v3.4.0** | Feb 2025 | **Complete + Plugins**: 36 skills, 15 plugins, 5 custom, 70+ aliases |
| v3.3.0 | Feb 2025 | Complete installation: 41 skills, memory system, MCP registration, 50+ aliases |
| v3.2.0 | Feb 2025 | Added 6 native skills, memory init, MCP registration |
| v3.1.0 | Feb 2025 | Added worktree-manager, vercel-deploy, statusline pro |
| v3.0.0 | Feb 2025 | Initial release with Claude Flow V3 |

---

<div align="center">

**Built with 💜 for the Claude ecosystem**

![Version](https://img.shields.io/badge/v3.4.0-2025--02-blue?style=flat-square)

*All 41 skills. All 15 plugins. All 175+ MCP tools. All 70+ aliases. One command.*

</div>
