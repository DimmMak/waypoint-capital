# ⚙️ Methodology

> How Blue Hill Capital actually makes decisions.

---

## 🎭 The three-tier architecture

```
┌────────────────────────────────────────────────────────┐
│  RESEARCH TIER (active thinking)                        │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━                       │
│  royal-rumble — 13-legend investment committee          │
└────────────────────────────────────────────────────────┘
                          │
                          ▼
┌────────────────────────────────────────────────────────┐
│  STORAGE / OBSERVABILITY TIER (passive memory)          │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━                       │
│  accuracy-tracker     — scores calls vs reality         │
│  trade-journal        — captures decisions              │
│  catalyst-calendar    — tracks upcoming events          │
│  [journalist]         — turns output into reports       │
└────────────────────────────────────────────────────────┘
                          │
                          ▼
┌────────────────────────────────────────────────────────┐
│  EXECUTION TIER (actual trades)                         │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━                       │
│  Chase Traditional IRA (external broker)               │
└────────────────────────────────────────────────────────┘
```

Mirrors real hedge fund structure: analyst team → ops desk → trading desk. Implementation is different. Pattern is identical.

---

## 🎯 The research engine: royal-rumble

13 legendary investors, each a domain expert:

**Voting legends (determine score):**
| Legend | Pillar | Weight |
|---|---|---|
| ⚡ Druckenmiller | Tactical Macro & Timing | 20% |
| 👑 Tom Lee | Liquidity & Macro Regime | 15% |
| 🚀 Cathie Wood | Disruptive Innovation | 15% |
| ⚖️ Ray Dalio | Risk & Portfolio Construction | 15% |
| 🏛️ Seth Klarman | Deep Value & Margin of Safety | 10% |
| 📐 Jim Simons | Quantitative & Data Edge | 10% |
| 🌀 George Soros | Sentiment & Narrative | 10% |
| 🎯 The Vol Desk | Options & Volatility | 5% |

**Advisory legends (shown, no vote until validated):**
Howard Marks · Trend Follower · Warren Buffett · Bill Ackman · Jim Rogers

Each legend runs in a **sealed subagent** — a fresh conversation context with no access to the parent session. Blindness is physical. The Judge synthesizes across all 13 into a weighted verdict.

Full technical detail: [royal-rumble repo](https://github.com/DimmMak/royal-rumble).

---

## 🧭 The decision flow

```
IDEA         →   .rumble TICKER   (13-legend blind committee)
         │
  pre-register your own hypothesis
         │
         ▼
RESEARCH     →   Committee debates, Judge synthesizes, verdict issued
         │
  compare YOUR call to THE JUDGE (divergence scored)
         │
         ▼
DECISION     →   Position sizing per conviction (Full/Half/Quarter/Starter/Pass)
                 IRA constraint enforced (max 20% per position)
         │
         ▼
EXECUTION    →   Order placed in Chase IRA (usually GTC limit)
                 Stop-loss written in trading journal
         │
         ▼
AUDIT        →   Thesis + entry + exit criteria logged to trades/TICKER.md
                 predictions.json appended with full committee state
         │
         ▼
CHECK-IN     →   30d / 60d / 90d reviews. Score call. Update track record.
```

---

## 📐 The commands

| Command | Use case |
|---|---|
| `.rumble TICKER` | Single-ticker deep-dive with hypothesis pre-registration |
| `.compare A vs B` | Parallel blind rumbles for head-to-head decisions |
| `.strategy THEME TIMEFRAME` | Thematic committee meeting → portfolio plan |
| `.challenge LEGEND argument` | Defend-mode debate with a single legend |
| `.log` | Track record review |
| `.checkin TICKER` | [stub] Score a prior rumble against reality |
| `.portfolio` | [stub] Review all current holdings |
| `.watchlist [list]` | [stub] Rank a provided universe |

---

## 🛡️ The discipline mechanisms

Three safety rails that run on every rumble:

1. **Fabrication Guard** — scans every legend's analysis for invented specifics (analyst targets without named analyst, MAs without chart source, TAM figures without cited report). Flagged claims surface as warnings.

2. **Cite-or-Abstain Rule** — every specific number must carry one of four tags: `[SRC: S1-S5]`, `[REPORTED]`, `[ESTIMATE]`, `[UNVERIFIED]`. Missing framework inputs → legend declares ABSTAIN or NEUTRAL with "data gap" note.

3. **Subagent Isolation** — the user's pre-registered hypothesis is *sealed* in the parent session and never passed to the blind committee subagent. The 13 legends analyze independently, then the parent compares their verdict to the user's prior view.

---

## 🎭 The killer insight

Every feature in the system exists to **turn opinion into measurable, auditable research**. The product isn't the verdicts. It's the **audit trail**. Every rumble is another data point. After 50 rumbles, the accuracy tracker tells a story that no pitch deck can fake.

**Our methodology IS our moat.** 🃏⚔️
