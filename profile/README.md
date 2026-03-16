# Clawmapper

**AI-agent-managed product roadmaps. No app. No database. Just markdown, git, and Claude.**

Clawmapper is an open-source system for managing product roadmaps through conversation with an AI agent. You tell it what you're building, what shipped, what changed — it structures everything, maintains consistency, and commits it to your repo. Your team reads the roadmap on GitHub. Stakeholders get generated outputs (slides, summaries, reports) on demand.

---

### How it works

1. **Clone the template** — `clawmapper/clawmapper` is the starting point
2. **Open it with Claude** — the `CLAUDE.md` tells the agent everything it needs to know
3. **Talk to it** — describe your roadmap in plain language; the agent writes and commits the markdown
4. **Share outputs** — ask for a board slide, a sprint summary, a stakeholder update; the agent generates and commits it

---

### Principles

- **No schema.** Markdown is flexible. Structure evolves with your team, not against it.
- **Git is the audit trail.** Every change is a commit. History is free.
- **The agent owns the roadmap.** Users don't edit files directly — consistency is the agent's job.
- **Outputs on demand.** HTML, PDF, slides — generated from the roadmap and committed back.

---

### Get started

```bash
gh repo clone clawmapper/clawmapper my-roadmap
cd my-roadmap
# Open in Claude Code and start talking
```

→ [clawmapper/clawmapper](https://github.com/clawmapper/clawmapper)
