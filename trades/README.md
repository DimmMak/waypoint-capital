# 📁 Trades Directory

Every trade gets its own markdown file. Standard format below.

Filename: `YYYY-MM-DD-TICKER.md`

---

## Template (v2 — enforces research discipline)

```markdown
# [TICKER] — [Entry Date]

## Entry
- Shares: [N]
- Price filled: $[X.XX]  [SRC: Chase IRA confirm]
- Capital committed: $[X.XX] ([X]% of account)
- Order type: [GTC Limit / DAY Market / etc]

## Bull thesis (before entry) — why we're buying
[One paragraph. Every specific number tagged: [SRC: ...], [REPORTED], 
[ESTIMATE], or [UNVERIFIED]. Don't leave numbers floating untagged.]

- Champion legend(s): [who liked it in the rumble]
- User hypothesis: [if pre-registered]

## BEAR CASE — what has to be true for us to be wrong (MANDATORY)
1. [specific testable condition]
2. [specific testable condition]
3. [specific testable condition]

**This section is non-negotiable. Even when bullish. Especially when bullish.**

## Exit plan (set BEFORE entry)
- Target: $[X] ([+X]%)
- Stop: $[X] ([-X]%)
- Stop basis: [2x ATR / 200-day MA / thesis-break condition]
- Time stop: [if no movement in X days, reassess]

## Invalidation triggers (any one kills the thesis — different from bear case)
Bear case = conditions that make the thesis wrong in theory.
Invalidation triggers = conditions that force an EXIT in practice.

1. [specific, testable, time-bound event]
2. [specific, testable, time-bound event]
3. [specific, testable, time-bound event]

## Source rumble
- Link: [../rumble or predictions.json entry]
- Judge verdict: [STRONG BUY / BUY / HOLD with size]  [SRC: predictions.json DATE]
- User-vs-Judge divergence: [AGREE / MILD / MODERATE / STRONG]

## Check-ins (add as time passes — never edit past entries)
- 7-day [DATE]: [price, thesis status, action taken]  [SRC: ...]
- 30-day [DATE]: [...]
- 60-day [DATE]: [...]
- 90-day [DATE]: [...]

## Exit (when it happens)
- Date: [YYYY-MM-DD]
- Price: $[X.XX]  [SRC: Chase fill]
- P&L: $[X] ([+/-X]%)
- Reason for exit: [target hit / stop hit / thesis invalidated / rebalance]

## Post-mortem (written within 48h of exit)
- What went RIGHT:
- What went WRONG:
- Legend that was MOST right:
- Legend that was MOST wrong:
- Was our bear case correct? (yes/no/partially)
- Lesson for next trade (one sentence):
```

---

## The three discipline rules enforced by this template

```
Rule 1 — Idea folders > source folders
  Every ticker gets one folder. This file lives in trades/TICKER/ or
  trades/YYYY-MM-DD-TICKER.md at root. Never in "articles/" or "reports/".

Rule 2 — Every memo has a bear case
  Section is MANDATORY above. Cannot be blank. Cannot be "none obvious."
  If you can't name a bear case, you don't understand the thesis yet.

Rule 3 — Every claim that can be challenged gets a tag
  Specific numbers + forecasts + quotes = must have [SRC: ...] or similar.
  General observations = optional.
  See /RESEARCH-DISCIPLINE.md for full tagging schema.
```

---

## Rules

1. **Fill thesis + bear case + exit plan BEFORE entering.** No trade without all three.
2. **Never edit the thesis or bear case after entering.** Post-fact rationalization is banned.
3. **Check-ins get added as time passes** — never edited.
4. **Post-mortem written within 48h of exit.** While it's fresh.
5. **When in doubt, add a tag.** When truly exhausted, drop to Tier-Minimum (see RESEARCH-DISCIPLINE.md).
