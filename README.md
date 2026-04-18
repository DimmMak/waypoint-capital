# 🗺️ Blue Hill Capital

> A **pre-alpha hedge fund** built from first principles —
> 13-legend investment committee, sealed-room research,
> every call pre-registered, every trade audited.

---

## 📊 At a glance

```
Stack cost:    $2.4k / year
Capital:       $7,000 Traditional IRA (Chase)
Horizon:       12-month audited track record  →  Year 2 friends/family  →  Year 3 formal fund
Current phase: pre-alpha v0.9 infrastructure
Rumbles:       6 logged    |    Strategy meetings: 1    |    Head-to-heads: 1
Blowups:       0
```

---

## 🧬 Philosophy in 5 lines

1. **Process > parameters.** Perfect weights applied emotionally always lose to imperfect weights applied with discipline.
2. **Sealed rooms.** Analysts cannot see the PM's hypothesis. Ever. (subagent isolation)
3. **Pre-registration.** Every call is logged *before* catalysts play out. No hindsight bias.
4. **Cite or abstain.** Every number carries a source tag. No plausibility filling.
5. **Earn your features.** Nothing ships — no skill, no trade, no allocation — until pain is real and repeated.

See [PHILOSOPHY.md](PHILOSOPHY.md) for the full framework.

---

## 🏗️ The stack ($2.4k/year, ~1% of a Bloomberg seat)

```
Research:   Claude Max 5x                   $200/mo
Execution:  Chase Traditional IRA           $0
Storage:    predictions.json + GitHub       $0
Discipline: royal-rumble skill              $0
```

See [STACK.md](STACK.md) for why this works.

---

## 🎯 The process

**[royal-rumble](https://github.com/DimmMak/royal-rumble)** — a Claude skill that orchestrates a 13-legend investment committee:

| Command | Produces |
|---|---|
| `.rumble TICKER` | Blind-committee deep-dive on one name |
| `.compare A vs B` | Parallel head-to-head analysis |
| `.strategy THEME TIMEFRAME` | Thematic portfolio plan (Monday meeting) |
| `.challenge LEGEND` | Defend-mode debate with a single legend |

Output is **cited, structured, auditable** — and lives in this repo as a permanent thinking artifact.

See [METHODOLOGY.md](METHODOLOGY.md) for architectural detail.

---

## 📈 Track record

→ [TRACK-RECORD.md](TRACK-RECORD.md) (live performance log)

Currently: **1 trade pending Monday open** (NOW, 4 shares via GTC limit $75).

---

## 📐 Constraints

```
Account type:    Traditional IRA (long-only, no margin, no naked options)
Capital:         $7,000
Max positions:   4-5 concurrent (20% cap per position)
Max drawdown:    -15% account = full reassessment
```

See [CONSTRAINTS.md](CONSTRAINTS.md).

---

## 🗺️ Roadmap

- **Q2 2026:** First 3-5 trades. Build accuracy-tracker, trade-journal, catalyst-calendar.
- **Q3 2026:** 15+ rumbles. First 30d check-in data. Retire/graduate advisory legends.
- **Q4 2026:** Strategy meetings quarterly. Portfolio review skill.
- **Q1 2027:** 12-month audited track record — the artifact that opens Year 2 capital conversations.

See [ROADMAP.md](ROADMAP.md) for the full plan with gates.

---

## ⚖️ The honest pitch

No capital raised. No performance history. No formal structure.

What this repo *is*: a documented, auditable, git-logged investment process run by one person on a $7k IRA for 12 months to **earn** the right to manage outside capital.

What this repo *is not*: a pitch deck. An ad. An AUM claim.

**Build the track record. The fund follows the track record. Never the other way around.** 🃏⚔️
