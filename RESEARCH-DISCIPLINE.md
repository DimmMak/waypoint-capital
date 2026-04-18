# 🔬 Research Discipline

> The 3 non-negotiable rules of Blue Hill Capital research.
> Same rules professional hedge fund analysts follow. Applied to every human-written note AND every AI-generated output.

---

## 🎯 The three rules

### **Rule 1. Idea folders > source folders**

```
✅  blue-hill-capital/trades/NOW/
      2026-04-17-rumble.md
      2026-04-17-memo.md
      2026-04-22-earnings-reaction.md
      2026-05-01-thesis-refresh.md

❌  blue-hill-capital/articles/
      bloomberg-articles.md
      seeking-alpha-notes.md
      10K-filings.md
```

**Organize by IDEA, not by SOURCE.** Every ticker gets one folder. Everything about that ticker — rumbles, memos, news clips, notes, reactions — lives in it.

**Why:** when you revisit NOW six months later, you want all the context in one place. Not scattered across "articles I read" and "reports I saved." Sources age. Ideas persist.

---

### **Rule 2. Every memo has a bear case. Always.**

```
✅  Bull memo required sections:
    1. Why we're buying
    2. What has to be true for us to be right
    3. BEAR CASE — what has to be true for us to be wrong
    4. Invalidation triggers — specific, testable conditions

✅  Bear memo requires same format, inverted.
```

**Even when you're bullish. Especially when you're bullish.** The contrarian anchor in royal-rumble does this automatically. Carry the same discipline to every human-written note.

**Why:** confirmation bias kills portfolios. Forcing the bear case in writing prevents the "I read 5 bull articles and now I'm certain" failure mode. A bear case you can't name = a thesis you don't understand.

---

### **Rule 3. Every claim that can be challenged gets a tag.**

**Required tag format:**
```
[SRC: <source>]              e.g., [SRC: S1], [SRC: 10-Q Q4 2025], [SRC: Bloomberg 4/17]
[REPORTED — <quarter>]       for figures from public filings
[ESTIMATE]                   for analyst-style projections (your math shown)
[UNVERIFIED]                 honest gap — you can't confirm this
[CONFIDENCE: H/M/L]          optional, attach to predictions or subjective claims
```

**Applied to:**
- All specific numbers (prices, revenues, multiples, growth rates)
- All forecasts ("we expect X by Q3")
- All quoted claims ("management said...")
- All percentage comparisons ("30% below peers")

**NOT required for:**
- Obvious facts ("NVDA makes chips")
- Pure opinions labeled as such ("I think this is overvalued")
- Meta commentary ("this memo is 500 words")

---

## 🛡️ The anti-fatigue fallback

If tagging feels like tax on any given day, downshift to **Tier-Minimum mode:**

```
TIER-MINIMUM (if tired / rushed):
  ✅ Must tag: specific numbers, forecasts, direct quotes
  ⬜ Skip:     general observations, flavor text
  ❌ NEVER skip: Rule 1 (folders) or Rule 2 (bear case)
```

**Rule 3 can flex. Rules 1 and 2 cannot.** Bear case is architectural. Tagging is discipline.

---

## 📐 Example — a properly disciplined note

```markdown
# NOW — Thesis refresh after 30 days (2026-05-17)

## Bull thesis (if still holding)
NOW closed at $94 today [SRC: Chase IRA], up 12% from our $83 entry on 2026-04-20.
The bullish driver: Agentforce ARR reportedly re-accelerated to +330% YoY
in Q1 2026 [SRC: Q1 2026 earnings call, 2026-05-04], validating the platform thesis.

Price reclaimed the 200-day MA at $110 [SRC: TradingView, confidence: H] —
a technical confirmation the trend-follower in our committee flagged would
matter. [SRC: royal-rumble 2026-04-17 rumble on NOW]

## What has to be true for us to be right (continued upside)
1. Q2 earnings confirm Now Assist ACV trajectory above $1B pace
2. Microsoft fails to displace ServiceNow in a named enterprise deal
3. Hyperscaler 2026 capex not guided down at June Fed meeting aftermath

## BEAR CASE — what has to be true for us to be wrong
1. Q2 miss on guidance (any magnitude >5%) — invalidation trigger
2. MSFT announces major ServiceNow displacement in named customer
3. Renewal rate falls below 95% (decay of moat)
4. Any hyperscaler cuts 2027 capex guide >10% [UNVERIFIED — we'd learn this
   on next quarterly guidance round]

## Action
Holding. Stop moved from $72 to $85 (just below $88 swing low) [CONFIDENCE: H
on mechanical rule, M on exact level]. Next check-in: 2026-06-17.
```

**Every claim tagged. Bear case present. Lives in `trades/NOW/`.** 🎯

---

## 🎭 The deepest insight

```
Professional discipline is just retail discipline with one extra loop:
  → Retail: "I think NVDA goes up"
  → Pro:    "I think NVDA goes up  [SRC: my model]  
             [CONFIDENCE: M]
             and I'm wrong if revenue decelerates below 40%  [BEAR CASE]
             in the NVDA folder alongside all prior thinking."

The extra loop is 20 seconds per claim.
Over 12 months it's the difference between
a trader and a portfolio manager.
```

**You now have all three disciplines documented.** Apply to every future note, trade memo, journal entry, retro. 🃏⚔️

---

## 🔗 Cross-references

- **Cite-or-Abstain** (royal-rumble PRE-STEP) — programmatic version of Rule 3
- **Contrarian Anchor** (Judge STEP 7) — programmatic version of Rule 2
- **trades/ folder structure** (already in blue-hill-capital) — implementation of Rule 1
- **CONSTRAINTS.md** — sizing + stop discipline to pair with research discipline
