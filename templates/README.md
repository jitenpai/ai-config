# Agent Templates

Baseline `.md` files for onboarding new agents at Hospitality.One.

## Usage

1. Copy all template files to the new agent's workspace directory
2. Replace all `[bracketed placeholders]` with agent-specific values
3. Customize SOUL.md personality and role sections
4. Have the agent acknowledge the Security Policy on Confluence
5. Set up weekly memory prune cron (Sundays 10 PM ET → #agent-automations)
6. Commit to version control

## Files

| File | Purpose |
|------|---------|
| `SOUL-base.md` | Personality, role, standing directives |
| `IDENTITY-base.md` | Quick-reference identity card |
| `AGENTS-base.md` | Workspace config, team structure |
| `MEMORY-base.md` | Long-term memory with company context |
| `PRODUCT-CONTEXT.md` | Current product state — MVP scope, KPIs, blockers, decisions (auto-updated weekly by Clawd Nine's cron, owned by Clawdia) |

## Standing Directives (baked into templates)

- Automations announce to #agent-automations (C0AE7PGMXTQ)
- Cron failures explicitly posted to #agent-automations
- Action Items page (2359319) updated on status changes
- Weekly memory prune — keep MEMORY.md under 200 lines
- Security Policy acknowledgment required

*Created: 2026-02-10 by Clawd Nine (CTO)*
