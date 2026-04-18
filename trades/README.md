# 📁 Trades Directory

Every trade gets its own markdown file. Standard format below.

Filename: `YYYY-MM-DD-TICKER.md`

---

## Template

```markdown
# [TICKER] — [Entry Date]

## Entry
- Shares: [N]
- Price filled: $[X.XX]
- Capital committed: $[X.XX] ([X]% of account)
- Order type: [GTC Limit / DAY Market / etc]

## Thesis (before entry)
- Why this: [one paragraph]
- Champion legend(s): [who liked it in the rumble]
- User hypothesis: [if pre-registered]

## Exit plan (set BEFORE entry)
- Target: $[X] ([+X]%)
- Stop: $[X] ([-X]%)
- Stop basis: [2x ATR / 200-day MA / thesis-break condition]
- Time stop: [if no movement in X days, reassess]

## Invalidation triggers (any one kills the thesis)
1. [specific testable event]
2. [specific testable event]
3. [specific testable event]

## Source rumble
- Link: [../rumble or predictions.json entry]
- Judge verdict: [STRONG BUY / BUY / HOLD with size]
- User-vs-Judge divergence: [AGREE / MILD / MODERATE / STRONG]

## Check-ins (fill as time passes)
- 7-day: [price, thesis status, action taken]
- 30-day: [...]
- 60-day: [...]
- 90-day: [...]

## Exit (when it happens)
- Date: [YYYY-MM-DD]
- Price: $[X.XX]
- P&L: $[X] ([+/-X]%)
- Reason for exit: [target hit / stop hit / thesis invalidated / rebalance]

## Post-mortem
- What went RIGHT:
- What went WRONG:
- Legend that was MOST right:
- Legend that was MOST wrong:
- Lesson for next trade (one sentence):
```

---

## Rules

1. **Fill thesis + exit plan BEFORE entering.** No trade without a doc.
2. **Never edit the thesis after entering.** Post-fact rationalization is banned.
3. **Check-ins get added as time passes** — never edited.
4. **Post-mortem written within 48h of exit.** While it's fresh.
