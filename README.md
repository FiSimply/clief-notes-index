# Clief Notes - Community Resource Index

**A community-maintained index of tools, skills, and frameworks shared on [Clief Notes](https://skool.com/cliefnotes) (Jake Van Clief's AI systems community).**

Skool's search is good for finding posts you already know exist. Not great for finding what you missed. So I built this.

---

## What's in Here

| File | Purpose |
|------|---------|
| `clief-notes-community-index.html` | **Shareable version** — open in any browser. Searchable, categorized. "Leave Review" button generates a formatted Skool reply; "Submit a Tool" button generates a submission template for Resources & Finds. |
| `clief-notes-index.html` | **Personal reference** — same catalog, adds local starring and private notes per tool via browser localStorage. |

Open either file directly in your browser. No server, no login, no dependencies.

---

## What's Indexed

**72 tools across 7 categories (Mar–Jun 2026):**

- **Memory & Context** — PMM, Session Memory Layer, Cortex, PMM Folder Template (Non-Technical), Codebase Memory MCP
- **ICM / Workspace** — Brofessor, ICM-Builder, ICM Workspace Architect, Foundations Tutor, Dev Fundamentals Tutor, CoworkOS Template, IBE Workflow Template, ICM Knowledge Vault, ICM on Local Models, sem_debug, Folder-is-the-Framework, Shipyard, Diana Agency Assistant, Creator Orchestrator Template, YouTube Tutor Template, Pipeline-As-File-Architecture (PAFA), ICM Specialist Coaches, ICM-Copilot-Cowork
- **Writing & Feedback** — Critical Editor, Council of 5, LinkedIn Content Wizard
- **Design & UI** — tastecheck, Weirdness Engine, DESIGN.md Extractor, Open Design, art-direct, Shade\_
- **Media & Content** — to-md, Pushing-Creation, YouTube Extraction Pipeline, TypeWhisper, Pushing Talk\_
- **Workflow & Utility** — Prompt Queen, Brainstorming Skill, pi-skills, Marketing Skills 2.0, Vercel Agent-Browser, Desktop Shortcut Launcher, Praxis Library, ARI-OS, Astrid, Magpie-search, scroll-screen-player, Gordon, VERA, The Source AI, TaskSystem, Pushing-Dispatch, Idea Vault, Agent Benchmarking Workflow, Obsidian ACE Method Skills, SkillOpt, Nightwatch, Porter, The Maintainer, RepoRouter, Subscription Auditor
- **External Frameworks** — Daniel Miessler's PAI, Hermes Agent, Open Brain, jcode, Understand Anything, icm-cctv, GiTeam, Dreaming Memory Kit, Zuki Personal AI OS, Signal Harmonics

---

## How to Contribute

Two ways to add a tool:

**Option 1 - GitHub PR (preferred)**
1. Fork this repo
2. Add your tool to the `TOOLS` array in both HTML files (follow the existing format below)
3. Open a pull request

**Option 2 — Post in Clief Notes**
Use the "Submit a Tool" button in the community index. It generates a formatted submission you paste into Resources & Finds. I'll add it.

---

## Tool Entry Format

```javascript
{
  id: "unique-id",
  name: "Tool Name",
  author: "Creator Name",
  cat: "memory|icm|writing|design|media|workflow|external",
  desc: "2-4 sentences. What it does, who built it, key mechanism.",
  links: [
    { label: "GitHub", url: "https://github.com/...", type: "github" },
    { label: "Community Post", url: "https://skool.com/cliefnotes/...", type: "community" },
    { label: "Site name", url: "https://...", type: "site" },
  ]
}
```

Community file uses a compact link format: `{l:"label", u:"url", t:"type"}`

---

## Context

Scanned: Resources & Finds and Show Your Work categories (Mar–Jun 2026). Coverage is solid for that window. Earlier posts and posts outside those two categories likely have more worth indexing.

This community generates real work. It deserves a proper catalog. Contributions keep it useful.

---

*Maintained by [@FiSimply](https://github.com/FiSimply) · Community: [skool.com/cliefnotes](https://skool.com/cliefnotes)*
