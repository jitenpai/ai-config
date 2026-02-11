# Product Context — Hospitality.One

*Owner: Clawdia (CPO) · Last updated: 2026-02-11*

## What We're Building
Unified analytics dashboard for multi-property hotel operators. One view across all properties — occupancy, revenue, performance — updated daily.

## Where We Are
- **Stage:** Pre-MVP, pre-discovery
- **Target partner:** EOS Hospitality (60+ properties, Oracle OPERA Cloud PMS)
- **Tech:** OHIP APIs (Oracle Hospitality Integration Platform)
- **Constraint:** OPERA Cloud only — no legacy OPERA on-prem

## MVP Scope (P1 KPIs)
11 KPIs, 9 fully viable via OHIP, 1 partial, 1 deferred:

| # | KPI | Status |
|---|-----|--------|
| 1 | Booked Room Nights | ✅ |
| 2 | Stayed Room Nights | ✅ |
| 3 | Show Rate | ⚠️ Partial |
| 4 | Paid Nights | ✅ |
| 5 | Avg. Occupied Rooms/Day | ✅ |
| 6 | Occupancy % | ✅ |
| 7 | ADR | ✅ |
| 8 | RevPAR | ✅ |
| 9 | Turndown/Denial Rate | ❌ Phase 2 |
| 10 | Double Occupancy Rate | ✅ |
| 11 | Stayover Rate | ✅ |

## Key Documents (Confluence)
- **PRD v0.1** — single source of truth for product success metrics
- **KPI Definitions v1.0** — business-facing KPI reference
- **KPI Feasibility Analysis v1.0** — technical viability per KPI
- **MVP Strategy v0.1** — scope and approach
- **Product Roadmap** — timeline and milestones
- **R&D Partner Deck v1.0** — for potential customers/partners
- **EOS Discovery Prep Deck** — internal only, pre-meeting brief

## Brand
- **Colors:** Navy `#1B2A4A`, Hospitality Gold `#C8963E`, Text Gold `#8B6914`
- **Font:** Plus Jakarta Sans (Google Fonts)
- **Logo:** Concept A "The Convergence" (3-line mark) + Concept C wordmark

## Key Decisions
- No OPERA/EOS details on public-facing materials (competitive sensitivity)
- No revenue numbers on docs pre-discovery
- Daily KPI refresh for MVP (real-time is future)
- PMS-only for MVP — zero POS dependency
- Discovery-first approach for EOS meeting (listen, don't pitch)
- "Stages" for SDLC cadence, "Releases" for product scope

## Current Priorities
1. EOS discovery meeting (awaiting stakeholder contacts from founders)
2. Prototype build against 9 P1 KPIs with sandbox data
3. Architecture doc + prototype plan (Clawd Nine)
4. Landing page deployment (Vercel)

## What's NOT in MVP
- POS integration
- Real-time data
- Legacy OPERA on-prem support
- Turndown/Denial Rate KPI
- Multi-PMS support
