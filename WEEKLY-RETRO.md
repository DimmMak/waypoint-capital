# 📅 Weekly Retro — Blue Hill Capital

> Every Sunday. 30 min. The mechanism that turns daily prodding into compounded improvement.

**Format:** copy the template below, fill in, commit. Past retros accumulate — they ARE the track record.

---

## 📝 TEMPLATE (copy for each new week)

```markdown
## 2026-W## (Mon-Sun dates)

### Activity
- Rumbles run:           N
- Compares run:          N
- Strategy meetings:     N (usually 0-1)
- Trades placed:         N
- Trades closed:         N

### Accuracy (from .accuracy summary)
- Single-ticker hit rate:  X/Y (Z%)
- Pair-relative hit rate:  X/Y (Z%)
- Best-performing legend:  [name + hit rate]
- Worst-performing legend: [name + hit rate]

### Gaps caught (from GAP-LOG.md)
- Total: N
- Fixed same-day: N
- Fixed this week: N
- Still open: N (list them)

### Ships this week
- [version] → [what it did]
- ...

### Weak points identified
1. [specific vulnerability]
2. [specific vulnerability]

### Next week priorities (max 3)
1. [specific ship OR rumble OR research task]
2. [...]
3. [...]

### The one lesson
[ONE sentence you want to remember in 6 months]

### Capital discipline check
- Current capital:           $XXXX
- Positions open:            N (within 4-5 max?)
- Cash reserve %:            X% (>= 15%?)
- Any invalidation triggers hit? (yes/no + which)
- Any risk rule broken?      (yes/no + which — this is the one to review hardest)

```

---

## 🎯 RETROS LIVE HERE — chronologically (newest at top)

## 2026-W16 (Apr 13 – Apr 19) — Foundation Week

### Activity
- Rumbles run:        6 (TSLA, AMD, MU, CRM, NOW×2, and pending)
- Compares run:       1 (CRM vs NOW)
- Strategy meetings:  1 (AI 12mo)
- Trades placed:      0 (original NOW $75 GTC plan invalidated by stale-price bug)
- Trades closed:      0

### Accuracy
- 5 rumbles scored, 3 non-HOLD (AMD, MU, NOW)
- Hit rate: 3/3 = 100% on 1-day sample (NOISE — need 20+ rumbles)
- Pair: 1/1 HIT (CRM vs NOW — NOW outperformed, matching verdict)

### Gaps caught (from GAP-LOG.md) — 7 total
- Fixed same-day: 6
- Fixed this week: 7/7 (100%)

### Ships this week (13 versions across 11 skills)
- royal-rumble v0.1 → v0.9.3 (architecture + blind subagents + price-desk integration)
- blue-hill-capital v0.1.0 → v0.1.2 (fund docs + research discipline)
- journalist v0.1.0 (Marks-style memos)
- chief-of-staff v0.1 → v0.2 (attention filter + first dispatch command)
- price-desk v0.1 → v0.1.2 (live prices + menu + watchlist)
- fundamentals-desk v0.1.0 (live fundamentals)
- technicals-desk v0.1.0 (live technicals — death of web-sourced MAs)
- accuracy-tracker v0.1.0 (hypothesis scoring)

### Weak points identified
1. **Web-search data contamination** — shipped 3 desks to kill it (prices, fundamentals, technicals)
2. **Hypotheses weren't scored** — fixed with accuracy-tracker
3. **Single-context contamination** — fixed with subagent isolation
4. **Chief was read-only** — added dispatch via .chief watchlist

### Next week priorities
1. Do 3 REAL rumbles with full desks wired in
2. Place a real first trade when thesis is clean
3. Weekly retro becomes routine habit

### The one lesson
**Accuracy obsession beats feature count.** 11 skills shipped because each one closed a real data hole — not because they looked cool.

### Capital discipline check
- Current capital:    $7,000 (unchanged)
- Positions open:     0
- Cash reserve %:     100% (no deploy yet)
- Invalidation hits:  N/A (no positions)
- Rules broken:       none

---

## 🎭 The retro principle

```
A fund that reviews itself weekly gets 50x better over a year.
A fund that doesn't review — doesn't get better, it drifts.
```

**The retro is the habit. This file is the proof.** 🃏⚔️
