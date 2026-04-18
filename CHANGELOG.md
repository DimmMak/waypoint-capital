# CHANGELOG — Blue Hill Capital

Every material change to the fund: process, infrastructure, constraints, or track record.

---

## [2026-04-17] — v0.1.2 — Research Discipline codified

### Shipped
- `RESEARCH-DISCIPLINE.md` — the 3 non-negotiable research rules documented with examples
- `trades/README.md` v2 — trade template now REQUIRES bear case section + tagged claims
- `PHILOSOPHY.md` — added Rule 10 (Research Discipline) linking to the new spec

### The three rules (now enforced across every note)
1. **Idea folders > source folders** — organize by TICKER, not by source
2. **Every memo has a bear case** — mandatory section in every trade doc
3. **Every claim that can be challenged gets a tag** — `[SRC: ...]`, `[REPORTED]`, `[ESTIMATE]`, `[UNVERIFIED]`

### Why
Real hedge fund analysts follow these three rules. Retail investors skip all three. The gap isn't raw data access — it's research discipline. Documented to be enforceable going forward.

### Anti-fatigue fallback
Rule 3 (tagging) can flex to Tier-Minimum mode (numbers/forecasts/quotes only) when exhausted. Rules 1 and 2 (folders, bear case) cannot flex — they're architectural.

---

## [2026-04-17] — v0.1.1 — Org Chart added

- `ORG-CHART.md` — brand names mapped to real hedge fund titles
- `role:` field added to royal-rumble, chief-of-staff, journalist frontmatter

---

## [2026-04-17] — v0.1.0 — Fund inception

**Trigger:** 15 ships of `royal-rumble` (v0.1 → v0.9.1) produced a working research engine. Needed a home for the fund thinking itself — philosophy, methodology, constraints, track record — separate from the tool.

### Shipped
- `README.md` — one-page identity + philosophy + stack
- `PHILOSOPHY.md` — the 10 non-negotiable principles
- `METHODOLOGY.md` — three-tier architecture (research → storage → execution)
- `STACK.md` — $2.4k/year infrastructure vs $700k/year institutional stack
- `CONSTRAINTS.md` — IRA / $7k / sizing / stop-loss discipline
- `ROADMAP.md` — 12-month plan to track record
- `TRACK-RECORD.md` — live performance log (starts at $7k, 0 trades)
- `trades/README.md` — standard template per trade
- `trades/2026-04-20-NOW-PENDING.md` — first trade documented pre-entry
- `meetings/2026-04-17-AI-12mo.json` — AI strategy meeting from royal-rumble

### Pending
- First real trade (NOW GTC limit Monday 2026-04-20)
- First 30-day check-in (2026-05-17)
- `accuracy-tracker`, `trade-journal`, `catalyst-calendar` skills (Month 1)

---
