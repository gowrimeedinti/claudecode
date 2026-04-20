# Claude Code Knowledge Base

This repo is a working notebook and in-progress guide on Claude Code,
written for a Python backend + ML/data science team at Genpact.

## Repo layout

| Path | Purpose |
|------|---------|
| `docs/` | The guide — numbered sections, Markdown, meant to be read in order |
| `notes/` | Raw daily notes, date-prefixed (`YYYY-MM-DD-topic.md`), append-only |
| `transcripts/` | Real Claude Code session logs used as examples in the guide |
| `experiments/` | Throwaway prompts, configs, scripts — not meant to be polished |
| `figures/` | Exported images; `figures/src/` holds editable source files |
| `drafts/` | WIP sections being written before promotion into `docs/` |

## Docs sections

1. `01-intro` — What Claude Code is and why it matters
2. `02-mental-model` — How to think about agentic coding assistants
3. `03-setup` — Installation, auth, IDE integration, CLAUDE.md
4. `04-workflow` — Day-to-day usage patterns and best practices
5. `05-ml-specifics` — Notebooks, data pipelines, model training, eval loops
6. `06-anti-patterns` — Common mistakes and how to avoid them
7. `07-safety` — Permissions, hooks, sensitive data, prod guardrails

## House style

- Guide docs: clear prose, concrete examples, code blocks for commands
- Notes: quick and messy is fine — clarity over polish
- Transcripts: preserve verbatim, add a short header explaining what the session illustrates
- Experiments: include a one-line comment at the top explaining what you were testing
