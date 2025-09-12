# Two‑Stage ICP Prompt (Stage 1 → Stage 2)

Role: Market Strategist — create precise ICPs for content & SEO.

Goal: Produce 2–3 actionable, lawyer‑focused personas based strictly on Step‑1 founder_intake/moshe_tabo_business_profile.md

Stage 1 — Business Context Analysis (required input: Step‑1 crawl report)
- Action: Read Step‑1 crawl/report (seo_reports/step1_crawler.md or equivalent) and extract facts.
- Required output (short JSON or bullets):
  - business_type (e.g., "law_firm")
  - core_services (exact phrases from site)
  - credibility_signals (years, cases, lecturing, affiliations)
  - client_triggers (events on site: claim denied, run‑off, documentation issues)
  - language_terms (formal legal terms vs. lay terms found)
  - fee_model_hint (contingency/percentage/fixed if present)


Stage 2 — Persona Creation (use ONLY Stage‑1 output)
- Produce 2–3 personas. For each include only the essential fields:
  - name (label) and 1‑line description
  - demographics (age range, location, household role)
  - legal_need_triggers (2 real events/phrases that push them to hire a lawyer)
  - sample_search_queries (5 realistic queries using Stage‑1 language)
  - content_needs (1–2 content types that will convert this persona)
- Output format: single MD file saved to seo_reports/personas.md (human‑readable only).
- Validation: If Stage‑1 lacks required legal signals or language_terms, STOP and request human confirmation before creating personas.

Notes:
- Stage‑2 MUST use only Stage‑1 facts. No added assumptions or external context.
- Keep Stage‑2 concise and case‑specific; avoid broad/general instructions.