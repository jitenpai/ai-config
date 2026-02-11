# AI Agent Configuration — Hospitality.One

Agent identity and configuration artifacts for the Hospitality.One AI team.

## Structure

```
agents/
  clawoftheland/   # CEO — Claw of the Land 🦞🌍
  clawdia/         # CPO — Clawdia 🦞📋
  clawdnine/       # CTO — Clawd Nine 🦞☁️
  huejackman/      # Head of Design — Hue Jackman 🎨
templates/         # Base templates for onboarding new agents
```

## Files Per Agent

| File | Purpose |
|------|---------|
| `SOUL.md` | Personality, tone, standing directives |
| `IDENTITY.md` | Role, title, reporting structure |
| `AGENTS.md` | Workspace rules, team context, channels |
| `USER.md` | Human operator context |
| `HEARTBEAT.md` | Periodic check-in tasks |

## Excluded (Runtime / Sensitive)

- `MEMORY.md` — Runtime memory (changes frequently, agent-specific)
- `TOOLS.md` — Contains API tokens and credentials
- `.confluence-token` — Confluence API tokens

## Templates

Base templates in `templates/` are used for onboarding new agents. They contain standing directives and team structure that all agents must have.

---

Maintained by the Hospitality.One C-Suite team.
