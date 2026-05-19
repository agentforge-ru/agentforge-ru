# agentforge_ru

**Custom Claude Code subagents · MCP servers · Telegram bots with AI logic**

I build production-safe AI tooling for the Claude Code ecosystem. Anonymous-by-design Russian-speaking AI engineer, working through Kwork and Habr Freelance. 40+ custom subagents written, ~10 Claude skills, several MCP servers in production-style use.

---

## 🧰 What I do

```text
┌─ Custom Claude Code subagents      ── specialized agents for narrow workflows
│
├─ MCP servers (Python)              ── connect Claude to your data sources
│
├─ Telegram bots with AI logic       ── filtering, digesting, classifying, routing
│
└─ Claude Code setup + skills        ── configure for your team's workflow
```

I work in a narrow, well-defined niche. I do not do generic AI copywriting, web design, or no-code platform integrations.

---

## 📦 Featured projects

### Subagents

| Repo | What it does | Stack |
|---|---|---|
| [opportunity-scout](https://github.com/agentforge-ru/opportunity-scout) | Contrarian market-opportunity hunter: demand-first signal mining + 6 named methodologies (Inversion, Pre-mortem, JTBD, Blue Ocean) + hard kill criteria | Claude Code |
| [council-orchestrator](https://github.com/agentforge-ru/council-orchestrator) | Meta-agent: convenes 3-5 specialist subagents in parallel on cross-functional decisions, synthesizes consensus and dissent | Claude Code |
| [claude-readme-generator](https://github.com/agentforge-ru/claude-readme-generator) | Reads a codebase, produces an honest README with mandatory limitations section and zero marketing copy | Claude Code |

### MCP servers

| Repo | What it does | Stack |
|---|---|---|
| [mcp-sqlite-server](https://github.com/agentforge-ru/mcp-sqlite-server) | MCP server for SQLite — read/write tools with safety guards against destructive operations | Python, MCP SDK |
| [mcp-google-sheets](https://github.com/agentforge-ru/mcp-google-sheets) | MCP server for Google Sheets — read/write/append/list via service-account auth | Python, MCP SDK, Google API |

### Telegram bots

| Repo | What it does | Stack |
|---|---|---|
| [tg-news-digest-bot](https://github.com/agentforge-ru/tg-news-digest-bot) | AI-powered news digest: pulls RSS, ranks + summarizes via Claude, posts daily digest | Python, Anthropic SDK, feedparser |

---

## 🛠 Tech stack

- **Languages:** Python 3.10+ (primary), Markdown, SQL, YAML
- **AI:** Anthropic Claude (Haiku/Sonnet/Opus), OpenAI when client requires it
- **Claude tooling:** Claude Code, Claude Desktop, MCP (Python SDK)
- **Telegram:** aiogram, raw Bot API via httpx
- **Data:** SQLite, PostgreSQL (via psycopg), Google Sheets API
- **Workflow:** Git/GitHub, gh CLI, pyproject + setuptools

What I deliberately don't use: no-code platforms (n8n / Make / Zapier) unless a client requires them, JS-heavy front-ends (I'm backend-focused), iOS/Android native.

---

## 💼 Services

I take both **fixed-scope projects** (one-off builds with clear deliverables) and **monthly retainers** (ongoing maintenance + new agents/tools).

Typical scopes:

- Custom Claude Code subagent under your workflow — from 1 500 ₽ / 24-48 hours
- MCP server connecting Claude to a specific data source — from 3 500 ₽ / 3 days
- Telegram bot with AI logic (parser / digest / assistant) — from 2 500 ₽ / 48-96 hours
- Setup Claude Code + 3 custom subagents — from 2 500 ₽ / 2 days
- AI prompt-system for a specific profession (lawyer / marketer / teacher) — from 3 500 ₽ / 3 days
- AI-driven documentation generation (README, API docs, runbooks) — from 3 500 ₽ / 3 days

Every project ships with: git repo, README, video walkthrough, 2 revisions.

---

## 🤝 Hire me

- **Kwork (Russian-speaking, RUB):** [kwork.ru/user/agentforge_ru](https://kwork.ru/user/agentforge_ru) (active)
- **Habr Freelance (Russian-speaking, RUB):** *opening soon*
- **GitHub issues:** open one on any repo with `[hire]` prefix and I'll reply within 24 hours

I work anonymously (text + voice-over only, no face/identity). All communication in Russian or written English.

---

## 📜 Working principles

- **Honest scope.** Every project ships with a written "what's included / what's not" list. No surprise scope creep, no hidden cost.
- **Safety guards by default.** Tools that touch data have refuse-on-destructive flags. Writes are off until you flip them on explicitly.
- **Open code.** I prefer to deliver in a public-able git repo (with sanitized data) so you can re-use my approach. Private repos available on request.
- **No vendor lock-in.** Every project documents how to migrate off it, not just how to use it.

---

## 📊 Open-source stats

This profile is anonymous on purpose — no LinkedIn, no Twitter, no real name. The repositories you see are the portfolio. Every line of code is reviewable.

---

*Generated 2026-05-19. Last updated when projects ship.*
