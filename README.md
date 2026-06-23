# Clief Notes — Community Resource Index

**A community-maintained index of tools, skills, and frameworks shared on [Clief Notes](https://skool.com/cliefnotes) (Jason Van Clief's AI systems community).**

Built because Skool's native search doesn't aggregate well. This is the index the community deserved.

---

## What's in Here

| File | Purpose |
|------|---------|
| `clief-notes-community-index.html` | **Shareable version** — open in any browser. Searchable, categorized, includes a "Leave Review" button that generates a formatted Skool reply, and a "Submit a Tool" button that generates a formatted post template. |
| `clief-notes-index.html` | **Personal reference** — same content, adds local star/notes per tool via browser localStorage. |

Open either file directly in your browser. No server required.

---

## What's Indexed

**32 tools across 7 categories (Mar–Jun 2026):**

- Memory & Context (PMM, Session Memory Layer, Cortex)
- ICM / Workspace (Brofessor, ICM-Builder, ICM Workspace Architect, Foundations Tutor, Dev Fundamentals Tutor)
- Writing & Feedback (Critical Editor, Council of 5)
- Design & UI (tastecheck, Weirdness Engine, DESIGN.md Extractor, Open Design)
- Media & Content (to-md, Pushing-Creation, YouTube Extraction Pipeline, TypeWhisper)
- Workflow & Utility (Prompt Queen, Brainstorming Skill, pi-skills, Marketing Skills 2.0, Vercel Agent-Browser, Desktop Shortcut Launcher, Praxis Library)
- External Frameworks (Daniel Miessler's PAI, Hermes Agent, Open Brain, jcode, Understand Anything)

---

## How to Contribute

Found a tool that's missing? Two ways to add it:

**Option 1 — GitHub PR (preferred)**
1. Fork this repo
2. Add your tool to the `TOOLS` array in either HTML file (follow the existing format)
3. Open a pull request — I'll review and merge

**Option 2 — Post in Clief Notes**
Use the "Submit a Tool" button in the community index. It generates a formatted submission you can paste directly into the Resources & Finds category. I'll add it to the index.

---

## Tool Entry Format

```javascript
{
  id: "unique-id",
  name: "Tool Name",
  author: "Creator Name",
  cat: "memory|icm|writing|design|media|workflow|external",
  desc: "2-4 sentence description. What it does, who it's for, the key mechanism.",
  links: [
    { label: "GitHub", url: "https://github.com/...", type: "github" },
    { label: "Community Post", url: "https://skool.com/cliefnotes/...", type: "community" },
    { label: "Site name", url: "https://...", type: "site" },
  ]
}
```

---

## Context

This index was built from a catalog scraped via the Claude browser extension across the Resources & Finds category (224+ posts). Coverage is good for Mar–Jun 2026 but not exhaustive — earlier posts and non-Resources categories likely have more tools worth indexing.

The community is growing fast. Contributions keep this useful.

---

*Maintained by [@FiSimply](https://github.com/FiSimply) · Community: [skool.com/cliefnotes](https://skool.com/cliefnotes)*
