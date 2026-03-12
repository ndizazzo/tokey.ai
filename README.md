<div align="center">
  <img src="assets/tokey.svg" alt="Tokey" width="420" />
  <h1>Tokey — Issue Tracker</h1>
  <p>Bug reports &amp; feature requests for the Tokey platform</p>
</div>

---

> **This repository contains no code.** It exists solely as a public-facing issue tracker for the Tokey platform — an LLM inference simulator, benchmark runner, and supporting infrastructure.

## Apps & Components

| App / Package | Description |
|---|---|
| **web** | React frontend — simulation UI, token streaming, presets |
| **backend** | Hono API server — Prisma + PostgreSQL |
| **tui** | Interactive terminal UI — Ink + React |
| **agent** | Headless benchmark runner, spawned by TUI |
| **simulator** | LLM inference simulator engine |
| **core** | Shared utilities — DB, Docker, SSH, hardware |

## Filing an Issue

Use one of the structured templates below. They help us triage faster.

| Template | When to use |
|---|---|
| 🐛 **Bug Report** | Something is broken or behaving unexpectedly |
| 💡 **Feature Request** | You have an idea for a new capability |
| 📝 **Blank Issue** | Anything else — questions, docs gaps, general feedback |

👉 [Open a new issue](../../issues/new/choose)

## Before You File

1. **Search first** — [check existing issues](../../issues) to avoid duplicates
2. **Be specific** — include the affected component, steps to reproduce, and your environment
3. **One issue per report** — don't bundle multiple bugs into one issue

## Labels

| Label | Meaning |
|---|---|
| `bug` | Confirmed defect |
| `enhancement` | New capability or improvement |
| `question` | Needs clarification or discussion |
| `wontfix` | Out of scope or intentional behavior |
| `duplicate` | Already tracked elsewhere |
| `good first issue` | Suitable for new contributors |
| `web` / `backend` / `tui` / `agent` / `simulator` / `core` | Affected component |
| `priority: high` | Blocking or critical |
| `priority: medium` | Important but not blocking |
| `priority: low` | Nice-to-have |

## Security

**Do not file security vulnerabilities as public issues.** See [SECURITY.md](SECURITY.md) for responsible disclosure.
