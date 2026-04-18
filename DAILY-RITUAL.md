# ☀️ Daily Ritual — Blue Hill Capital

> The 3-minute minimum that turns a hedge fund from a repo into an operating system.

---

## 🌅 MORNING (10 min max)

```
[ ] .chief watchlist           — what moved overnight?
[ ] .accuracy summary          — hit rate trend this week
[ ] Read GAP-LOG last 3 days   — patterns?
[ ] Pick ONE thing to prod     — where does the system look weak today?
```

**One prod per day. Just one.** Not a project. Not a build. A question, a verification, a stress test.

---

## 🌙 EVENING (5 min max)

```
[ ] Log any gaps caught today to GAP-LOG.md
[ ] If 3+ gaps in same area this week → declare it a T1 ship
[ ] Review open positions (if any) vs invalidation triggers
[ ] .cash-out if session done
```

---

## 📅 WEEKLY (Sunday, 30 min)

```
[ ] Run .accuracy summary + rumbles + pairs
[ ] Update WEEKLY-RETRO.md
[ ] Tier-list unresolved GAP-LOG items
[ ] Ship the top T1 item (max 1 per week to avoid churn)
```

---

## 📆 MONTHLY (last Sunday, 2 hr)

```
[ ] Cross-all accuracy report — per-legend hit rate attribution
[ ] Stress test — pick 1 random rumble, audit every number cited
[ ] Update ROADMAP.md based on what was actually used vs ignored
[ ] Prune skills that haven't been used in 30 days (earn-your-features in reverse)
```

---

## 📊 QUARTERLY (every 3 months, 4 hr)

```
[ ] Major stress test — run full .test across 5 tickers
[ ] Calibration audit — are filter thresholds still correct?
[ ] Graduate/kill advisory legends based on measured signal
[ ] Write fund letter for the quarter (.journalist-assisted)
```

---

## 🎯 THE PROD — what to question today

Rotate through these surfaces. Each one ~once per 10 days:

```
🔴 HIGH-VALUE PRODS (prod these often):
  1. "Show me where the number X came from. Timestamp + source."
  2. "Re-run this rumble. Do you get the same verdict?"
  3. "What assumption is this thesis hiding that could break it?"
  4. "Which legend was most wrong on last week's rumbles? Why?"
  5. "If I run .chief watchlist twice in 5 min, do numbers match?"

🟡 MEDIUM PRODS (weekly):
  6. "What does the Fabrication Guard MISS?"
  7. "Is any skill reading from a data source I didn't verify?"
  8. "Which of my open positions has the stalest thesis?"

🟢 LOW PRODS (occasional):
  9. "What's the system's current single point of failure?"
 10. "If yfinance went down today, what still works?"
```

---

## 🎭 The meta-principle

```
Every prod is either:
  a) The system passes → your confidence compounds
  b) The system fails → you've just earned a T1 ship

Either outcome makes the fund stronger. There is no wasted prod.
```

---

## 💎 When you feel lazy

**Default: run `.chief watchlist` and `.accuracy summary`.** That's it. 2 commands. 10 seconds. Even on lazy days this keeps the habit alive.

**A hedge fund is run daily or it's not a hedge fund.** 🃏⚔️
