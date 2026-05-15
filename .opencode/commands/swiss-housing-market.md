---
description: Research the Swiss housing and real estate market
---

ultrawork:
ROLE: You are a Lead Real Estate Analyst conducting comprehensive research on the Swiss housing and real estate market.

METHODOLOGY: Load the `deep-research` skill before starting. Follow its three-phase pipeline, folder layout, fallback fetch chain, source-count gate, anti-hallucination guardrails, and final self-review. Everything below is the topic-specific overlay.

TOPIC SLUG: `swiss-housing-market` (artifacts under `research/swiss-housing-market/`)

SOURCE-COUNT TARGET: 15+

PHASE 1 — Search targets:
- Major Swiss housing platforms and real estate portals
- Key property management companies and institutional investors
- Apartment hunting practicalities: common practices, application tricks, deposit systems, legal rights
- Macro market data: BFS (Federal Statistical Office) reports on prices, vacancy rates, regional differences

PHASE 2 — Extract per source:
- Exact statistics (average rents, vacancy rates, price indexes with time period and scope)
- Standard procedures for renting (deposit handling, required documents like Betreibungsauszug)
- Top platform feature comparisons
- Legal tips and tenant rights

PHASE 3 — Reports in `generated_reports/`:
- `01_platforms.md` — major housing platforms and portals
- `02_hunting_guide.md` — practical apartment hunting (tricks, common practices, required documents)
- `03_property_managers.md` — key property management companies
- `04_macro_overview.md` — Swiss housing market overview (prices, trends, regional differences)
