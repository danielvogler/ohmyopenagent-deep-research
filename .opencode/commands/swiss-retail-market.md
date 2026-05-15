---
description: Research the Swiss retail market landscape
---

ultrawork:
ROLE: You are a Lead Retail Industry Strategist preparing a board-grade strategic briefing on the Swiss retail landscape. The output must read as an investment-grade competitive review — not a directory of facts. Every claim is sourced, every player is contextualised, every theme has a "so what".

METHODOLOGY: Load the `deep-research` skill before starting. Follow its three-phase pipeline, folder layout, fallback fetch chain, source-count gate, anti-hallucination guardrails, and final self-review. Everything below is the topic-specific overlay.

TOPIC SLUG: `swiss-retail-market` (artifacts under `research/swiss-retail-market/`)

SOURCE-COUNT TARGET: 50+

Recency: prefer sources from the last 3 years. Older sources only for historical context (M&A history, format evolution, leadership succession).

PHASE 1 — Mandatory search angles. Each must be exhausted before the source-count gate.

ANGLE A — Market structure and macro:
- Total Swiss retail market size and segmentation (food vs non-food, online share)
- BFS Detailhandelsumsatz and retail commerce data
- Swiss Retail Federation (Handelsverband.swiss / Schweizer Detailhandel) reports
- GfK Switzerland, NielsenIQ Switzerland consumer panel data
- UBS / Credit Suisse Swiss Retail Outlook reports (multi-year trajectory)
- Deloitte Global Powers of Retailing — Swiss sections
- PwC, KPMG, EY, BCG, McKinsey, Bain Switzerland retail publications

ANGLE B — Food retail incumbents (cooperatives, discounters, convenience):
- Migros Group: Migros supermarkets, Denner, Migrolino, Migrol, Hotelplan, Galaxus / Digitec, melectronics, SportXX, Micasa, Do it + Garden, Globus (divestment history), Ex Libris, the 2024-2025 restructuring
- Coop Group: Coop supermarkets, Coop Pronto, Coop Bau+Hobby, Coop Vitality, Interdiscount, Microspot, Toptip / Lumimart, Christ Uhren & Schmuck, Import Parfumerie, Jumbo, Mondovino, Marché Restaurants
- Foreign discounters: Lidl Schweiz, Aldi Suisse — format, store count, share
- Independents and convenience: Volg (Fenaco), Landi (Fenaco), Spar Schweiz, Otto's, Aligro

ANGLE C — Non-food specialty by vertical:
- Department stores: Manor, Globus (Central Group), Loeb, Jelmoli closure 2025
- DIY / Garden: Jumbo, Hornbach Schweiz, OBI Schweiz, Bauhaus, Coop Bau+Hobby, Migros Do it + Garden
- Electronics / appliances: Interdiscount, MediaMarkt Schweiz, Fust, Microspot, Brack.ch, Digitec Galaxus, melectronics
- Fashion / apparel: H&M Schweiz, Zara / Inditex, C&A, Tally Weijl, Chicorée, PKZ, Manor fashion, Globus fashion, Zalando.ch, Vögele Mode collapse 2022
- Pharmacy / drugstore: Coop Vitality, Sun Store, Amavita, Galenicare, Topwell, Müller Drogerie Schweiz
- Sport: SportXX (Migros), Ochsner Sport, Athleticum, Decathlon Schweiz, Intersport
- Furniture / home: IKEA Schweiz, Pfister, Conforama, Möbel Hubacher, Micasa (Migros), XXXLutz Swiss presence
- Toys / books: Franz Carl Weber, Smyths Toys (post-Toys"R"Us), Orell Füssli, Ex Libris (Migros)

ANGLE D — Online retail, marketplaces, cross-border:
- Domestic e-commerce: Galaxus / Digitec, Brack, Microspot, Coop@home, Migros Online (LeShop history), Mondovino, Zalando.ch
- Cross-border / international pressure: Amazon.de, Zalando, Shein, Temu, Wish
- Einkaufstourismus: estimated revenue leakage, FX dynamics, VAT thresholds

ANGLE E — Strategic and macro themes:
- Cooperative governance and its strategic implications (capital, reporting, time horizons, member economics)
- Private label penetration and own-brand strategy in CH
- Hard-discount disruption playbook (Aldi / Lidl) and incumbent response
- Omnichannel maturity and last-mile economics in CH
- Retail media networks — early signals at Migros / Coop
- Sustainability and ESG positioning (cooperative differentiators)
- Cost structure: labor, real estate, sourcing relative to EU
- Regional dynamics: DE / FR / IT Switzerland, urban vs rural

ANGLE F — Recent corporate activity (last 3 years):
- M&A: Globus sale (2020), Jelmoli closure (2025), Vögele collapse (2022), Migros portfolio streamlining (2024-2025)
- Format launches and closures, store count trajectories
- Leadership changes at Migros and Coop
- Financial performance trends from annual / sustainability reports

Topic-specific source diversity — saved sources should span at least 4 of these categories (this is in addition to the skill's general diversity rule):
(a) Government / statistical (BFS, regulatory bodies)
(b) Industry / trade publications (Handelszeitung, NZZ, Tages-Anzeiger, Schweizer Detailhandel)
(c) Consulting / advisory reports (Deloitte, PwC, KPMG, EY, BCG, McKinsey, Bain)
(d) Bank / equity research (UBS, Vontobel, ZKB)
(e) Corporate filings / annual reports (Migros, Coop, Galenicare, Valora, etc.)
(f) Consumer panel / market research (GfK, NielsenIQ)
If 3 or more of these categories are empty after the first pass, run one more targeted round per missing category before clearing the gate.

PHASE 2 — Extract per source, beyond the skill's generic fields:
- Hard KPIs: market share, revenue, gross / EBITDA / EBIT margin, store count, employee count, capex, e-commerce share, like-for-like growth, private label penetration, sales per sqm, basket size, ROIC where available
- Strategic moves and management commentary (verbatim where useful)
- Risk factors and forward-looking statements

Group findings into:
(a) Market structure and macro data
(b) Player profiles by segment (food, DIY, electronics, fashion, pharmacy, sport, furniture, online, department stores)
(c) Strategic themes (private label, omnichannel, ESG, retail media, Einkaufstourismus, cooperative governance, hard-discount)
(d) Corporate activity (M&A, restructuring, leadership)
(e) Forward-looking scenarios and disruption signals

PHASE 3 — Reports (4 markdown reports, 2,500–3,500 words each) in `generated_reports/`. Each report opens with a 5-7 bullet executive summary and closes with strategic implications.

1. `01_market_structure_and_forces.md`
   - Market size and segmentation (food, non-food, online) with multi-year trajectory
   - Cooperative-driven structural features and their strategic implications
   - Porter's Five Forces calibrated for Swiss retail (rivalry, buyer power, supplier power, new entrants, substitutes) — intensity rating with evidence
   - PESTEL of retail-critical factors (FX, labor cost, e-commerce regulation, cross-border tax, consumer sentiment, sustainability regulation)
   - Profit pool and value pool mapping across formats and channels
   - Where attractiveness is rising, stable, eroding

2. `02_competitive_landscape.md`
   - Player census by segment with revenue, share, store count, ownership
   - Strategic-positioning matrix: cost leader vs differentiator vs focused niche, plotted with concrete evidence per player
   - Channel and format polarization map (hard-discount vs convenience vs premium vs online-native)
   - Diversified group portfolios (Migros, Coop, Fenaco) plotted on a BCG-style growth-share view across their sub-brands
   - White-space and overcrowded niches

3. `03_company_deep_dives.md`
   - Deep profiles of Migros Group, Coop Group, plus 2-3 of (Denner, Lidl Schweiz, Galaxus Group, Manor, Fenaco) chosen by strategic significance
   - For each profile cover:
     * Corporate / cooperative structure and governance
     * Portfolio map (brands, sub-brands, subsidiaries) with revenue contribution
     * Value chain control (sourcing, logistics, store ops, brand, customer data)
     * Capability stack: what they uniquely do well (VRIO-style read)
     * Financial trajectory: revenue, gross / EBIT margin, capex intensity, working capital, ROIC where available
     * Recent strategic moves (last 24-36 months) and their rationale
     * Vulnerabilities and threat exposure (cross-border, discount, online, generational shift, sustainability laggards)
     * Two-to-three-year strategic trajectory and signals to watch

4. `04_strategic_themes_and_outlook.md`
   - Theme deep-dives, each with size of the prize, leaders / laggards, execution requirements, three-year outlook:
     * Private label premiumisation and own-brand economics
     * Omnichannel and last-mile in a high-cost, low-density geography
     * Retail media as a new profit pool
     * Hard-discount disruption arc — has it peaked?
     * Einkaufstourismus and the cross-border value leak
     * Sustainability / ESG as cooperative differentiator
     * Consolidation, M&A pipeline and portfolio rationalisation
   - Three-to-five-year scenarios with triggers, winners, losers
   - Five questions any Swiss retail executive should be answering now

Topic-specific quality bar — applied in addition to the skill's quality bar and final self-review:
- 5-7 bullet executive summary at the top of each report
- Strategic implications / "so what" at the close of each major section
- Tables for all structured comparisons (player matrices, KPI grids, framework intensity ratings)
- Source index at end of each report
- At least 4 of the 6 topic-specific source categories above are represented in the citation footprint
- Player census in `02_competitive_landscape.md` lists ownership, segment, revenue or store count, and a one-line strategic position for every player
- Each company deep dive in `03_company_deep_dives.md` covers all eight required sub-sections
- Each report contains the required frameworks (Five Forces, PESTEL, positioning matrix, theme table)
- Each report is within the 2,500–3,500 word target (note deviation if not)
