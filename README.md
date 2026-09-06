# OS — AI Operating System

A personal Claude Code OS kit. Three skills, six folders, one framework. Lean on purpose.

## Day 1 — Get started

1. Open this folder in Claude Code
2. Run `/onboard`
3. Answer 7 questions. That's it.

Claude will scaffold your `context/` files, `references/voice.md`, and `connections.md` from your answers.

## What's in the kit

| Item | Purpose |
|---|---|
| `CLAUDE.md` | Root operating manual. Filled by `/onboard`. |
| `aios-intake.md` | Source of truth for onboarding. Edit and re-run `/onboard` any time. |
| `connections.md` | Registry of every tool your OS can reach. |
| `context/` | About you, your business, your priorities. |
| `references/` | Frameworks, voice samples, API guides. |
| `decisions/log.md` | Append-only record of decisions and why. |
| `archives/` | Old files. Don't delete — move here. |
| `.claude/skills/` | Your skills: onboard, audit, level-up. Installed separately — see below. |

## Core skills

| Skill | When to run |
|---|---|
| `/onboard` | Day 1. Re-run after editing `aios-intake.md`. |
| `/audit` | Day 7, then weekly. Scores your setup against the Four Cs. |
| `/level-up` | Weekly, Friday. Finds and ships one automation. |

## Installing the skills

The three skills live in a separate repo. Clone it into `.claude/skills/`:

```
git clone <SKILLS_REPO_URL> .claude/skills
```

## Grow with `EXPANSIONS.md`

Read it when you feel like the kit is too small. It tells you what to add and when.

## Credits

This kit is a blend of learnings from three sources:

- **Nate Herk** — The Three Ms of AI™ (Mindset, Method, Machine). The framework in
  `references/3ms-framework.md` and the `/level-up` interview are adapted from his work.
  *The Three Ms of AI™ is a trademark of Nate Herk. © 2026 Nate Herk. All rights reserved.*
- **Sabrina Ramonov** — <!-- TODO: describe qué parte del kit viene de su trabajo -->
- **Hubert Thompson** — <!-- TODO: describe tu aporte propio -->
