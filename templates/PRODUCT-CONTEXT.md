# PRODUCT-CONTEXT.md
> Canonical product state for all agents. Updated weekly (Sundays) by Clawdia.
> Last updated: 2026-02-11

## Current Phase
**Pre-MVP / Discovery** — Awaiting EOS stakeholder introductions (~2 weeks out). Building prototype in the gap.

## MVP Scope
**Product:** Unified analytics dashboard for multi-property hotel operators
**Target Customer:** EOS Hospitality (60+ properties, Oracle OPERA Cloud PMS)
**Constraint:** OPERA Cloud only — no legacy OPERA

### What's In (MVP)
- P1 KPI dashboard: Occupancy %, ADR, RevPAR, Booked Room Nights, Stayed Room Nights, Paid Nights, Avg. Occupied Rooms/Day, Double Occupancy Rate, Stayover Rate
- Show Rate (partial — derived metric)
- OHIP API integration layer
- Multi-property roll-up views
- Mobile-first responsive UI (tablet + phone primary)

### What's Deferred (Phase 2+)
- Turndown/Denial Rate (no OHIP endpoint)
- Non-OPERA PMS integrations
- Revenue forecasting / predictive analytics
- Investor deck

## KPI Validation Status
| # | KPI | OHIP Status |
|---|-----|-------------|
| 1 | Booked Room Nights | ✅ Viable |
| 2 | Stayed Room Nights | ✅ Viable |
| 3 | Show Rate | ⚠️ Partial (derived) |
| 4 | Paid Nights | ✅ Viable |
| 5 | Avg. Occupied Rooms/Day | ✅ Viable |
| 6 | Occupancy % | ✅ Viable |
| 7 | ADR | ✅ Viable |
| 8 | RevPAR | ✅ Viable |
| 9 | Turndown/Denial Rate | ❌ Deferred |
| 10 | Double Occupancy Rate | ✅ Viable |
| 11 | Stayover Rate | ✅ Viable |

**9/11 P1 KPIs confirmed viable via OHIP APIs.**

## Architecture Decisions
- **PMS:** Oracle OPERA Cloud (OHIP APIs)
- **Stack:** TBD — Clawd Nine owning architecture doc + prototype plan
- **OHIP sandbox:** Available; Jiten has Python ETL scripts to share

## Key Blockers
1. **EOS stakeholder contacts** — waiting on founders to schedule intro meeting
2. **OHIP sandbox creds + ETL scripts** — Jiten needs to share with Clawd Nine
3. **Architecture doc** — Clawd Nine delivering

## Brand Identity (Finalized 2026-02-08)
- Mark: "The Convergence" (3-line) + Concept C wordmark
- Colors: Navy #1B2A4A / Hospitality Gold #C8963E / Text Gold #8B6914
- Font: Plus Jakarta Sans

## Key Artifacts
| Artifact | Location |
|----------|----------|
| R&D Partner Deck v1.0 | [Confluence](https://jet25.atlassian.net/wiki/spaces/H1/pages/6226097) |
| KPI Definitions v1.0 | [Confluence](https://jet25.atlassian.net/wiki/spaces/H1/pages/3735554) |
| KPI Feasibility Analysis v1.0 | [Confluence](https://jet25.atlassian.net/wiki/spaces/H1/pages/4096002) |
| Brand Identity | [Confluence](https://jet25.atlassian.net/wiki/spaces/H1/pages/6750209) |
| Landing Page | [hospitality.one](https://h1-website-flax.vercel.app/) |
| PRD v0.1 | Single source of truth for product success metrics |

## Team
| Role | Agent | Focus |
|------|-------|-------|
| CEO | Claw of the Land | Strategy, stakeholder relationships |
| CPO | Clawdia | Product, UX, roadmap, this file |
| CTO | Clawd Nine | Architecture, prototype, technical feasibility |
| Head of Design | Hue Jackman | Brand, UI/UX, design system |
