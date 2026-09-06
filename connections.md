# Connections

Registry of every system your OS can reach. Filled by `/onboard` from Q4-Q7 answers; expanded over time as you wire new tools. `/audit` checks this file for domain coverage and freshness.

| # | Domain | Tool | What it holds | Mechanism | Auth | Last checked |
|---|---|---|---|---|---|---|
| 1 | Revenue / Financials | [Your accounting tool] | [What it holds] | not yet connected | — | — |
| 2 | Customer interactions | [Your email] | [What it holds] | not yet connected | — | — |
| 3 | Calendar | [Your calendar] | [What it holds] | not yet connected | — | — |
| 4 | Communication | [Team/customer tool] | [What it holds] | not yet connected | — | — |
| 5 | Project / task tracking | [Your PM tool] | [What it holds] | not yet connected | — | — |
| 6 | Knowledge / files | [Docs/notes tool] | [What it holds] | not yet connected | — | — |

**Mechanism options:** `mcp` (MCP server), `script` (Python/Bash hitting an API, in `scripts/`), `export` (CSV/JSON dump pipeline), `key+ref` (`.env` key + `references/{tool}-api.md` guide), `not yet connected`.

When you wire a new tool, also save `references/{tool}-api.md` capturing endpoints, auth flow, and common queries — researched-once-saved-forever.
