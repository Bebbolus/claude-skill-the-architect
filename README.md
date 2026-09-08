# 🏛️ The Architect — Claude Code & Cowork Skill

[![Standard: Claude Skill](https://img.shields.io/badge/Standard-Claude%20Skill-blueviolet.svg)](https://github.com/Bebbolus/claude-skill-the-architect)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Zero-Bloat](https://img.shields.io/badge/Architecture-Zero--Bloat%20%284%20Archetypes%29-green.svg)](https://github.com/Bebbolus/claude-skill-the-architect)

The official, zero-context-bloat **The Architect** skill packaged for **Claude Code**, **Cowork**, and native LLM skill directories.

This skill transforms Claude into a deterministic **Systems Architect and Meta-Orchestrator** using the **Model Workspace Protocol (MWP)** and the **Interpretable Context Methodology (ICM)**. Instead of polluting conversational memory, it scaffolds structured directories, role contracts with invariant clauses (C1–C5), and compiles state directly to disk.

---

## ⚡ Instant Installation

### 1. Global Installation (Available across all your Claude Code projects)
Copy or symlink this folder to your user's global Claude skills directory:

```bash
mkdir -p ~/.claude/skills/the-architect
cp SKILL.md ~/.claude/skills/the-architect/SKILL.md
```

Or via git clone:
```bash
git clone https://github.com/Bebbolus/claude-skill-the-architect.git ~/.claude/skills/the-architect
```

### 2. Project-Local Installation (Specific repository)
If you want to bundle The Architect directly in a single project repository:

```bash
mkdir -p .claude/skills/the-architect
cp /path/to/claude-skill-the-architect/SKILL.md .claude/skills/the-architect/SKILL.md
```

---

## 🚀 How to Use

Once installed, simply invoke The Architect inside Claude Code:

```text
/the-architect
```
or prompt directly:
```text
Activate The Architect to structure this workspace into an autonomous pipeline.
```

The Architect will immediately run its **Triage State Machine**:
1. **State 0 (Environment Reconnaissance)**: Detects whether your workspace is Greenfield (new) or Brownfield (existing files) and asks how to treat existing files.
2. **State 1 (Triage Depth Selection)**: One direct question asking whether you prefer **Fast Triage** (3 questions) or **Deep Consultative Triage** (Socratic interview).
3. **Scaffolding Factory**: Deploys the standard directories (`0 - SISTEMA`, `1 - INBOX`, `2 - WORKFLOW`, `3 - CONOSCENZA`, `tmp/`) and the root pointer (`CLAUDE.md`).
4. **4 Core Generative Archetypes**: Drives task execution through **Maker**, **Checker**, **Recon**, and **Coder** without overloading system context.

---

## 🔒 Zero Context Bloat Guarantee

Unlike monolithic prompt packs that inject dozens of inactive roles into system memory, this skill is restricted strictly to the **4 generative archetypes** (<2.5k tokens), preventing context rot and preserving maximum cognitive bandwidth for complex reasoning.

---

## 📜 License
MIT © Bebbolus
