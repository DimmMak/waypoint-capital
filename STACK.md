# 🏗️ The Stack

> How Blue Hill Capital runs for **$2.4k/year** — roughly **1% of a Bloomberg seat**.

---

## 💰 Total cost breakdown

| Tier | Tool | Cost | Replaces |
|---|---|---|---|
| **Research** | Claude Max 5x | $200/mo ($2.4k/year) | Bloomberg ($24k), Factset ($15k) |
| **Execution** | Chase Traditional IRA | $0 | Prime broker ($50k+ setup) |
| **Storage** | Git + GitHub | $0 | OMS / Portfolio System ($50k+) |
| **Data** | Free web search (inside Claude) | $0 | Refinitiv ($22k) |
| **Analysis infra** | royal-rumble skill | $0 | Research team ($500k+ salary) |
| **Compliance** | N/A (personal IRA) | $0 | Legal/audit ($100k+/year) |
| **TOTAL** | | **$2,400/year** | **~$700k/year** |

---

## 🏛️ Why the cheap stack actually works

### What Bloomberg buys ($24k/seat/year)

```
✓ Clean, reconciled market data
✓ Point-in-time data (critical for backtests)
✓ Proprietary analyst notes
✓ Real-time news with sub-second latency
✓ Native analytics and Excel integration
```

### What we DON'T need it for (yet)

```
✗ Holding period: months/years, not milliseconds
✗ Universe size: 4-5 concurrent positions, not 500
✗ Frequency: 1-2 trades per month, not 10k/day
✗ AUM: $7k, not $7B
```

**Bloomberg's edge is in milliseconds + massive universe coverage. Neither applies to us.** Our edge is in **discipline + audit trail** — and those are free.

---

## 📊 Data quality — how we compensate for free sources

Free web search is noisy. Our three-rail discipline closes most of the gap:

1. **Cite-or-Abstain** — every number carries a source tag, every missing input becomes `[UNVERIFIED]`. No plausibility-filling.
2. **5 parallel searches per rumble** — diversified query design surfaces data conflicts, and we flag them explicitly rather than picking one silently.
3. **Curated dossiers (planned)** — the `.dossier` command will let us feed hand-picked articles (10-Qs, transcripts, analyst notes) into the committee for framework analysis, bypassing web search entirely.

**Conservative estimate: free web + discipline = 70% of Bloomberg data quality for our horizon.** At 1% of the cost.

---

## 🎭 The upgrade path (earned, not speculative)

| Trigger | Tool to add | Cost |
|---|---|---|
| 20+ rumbles + accuracy tracker live | Polygon.io or Alpha Vantage | $50-200/mo |
| Moving to taxable account w/ shorts | IBKR or Tastytrade (execution) | $0 + per-trade |
| 3-year track record + considering outside capital | SEC Exempt Reporting Adviser | $1-5k legal setup |
| Managing >$100M AUM (Year 5+) | Bloomberg Terminal | $24k/seat |

**Nothing upgrades until the prior tier is earned.** No speculative tools.

---

## 💎 The philosophical point

```
A hedge fund with Bloomberg and bad discipline → still loses.
A retail trader with free data and great discipline → beats most funds.

Infrastructure cost ≠ edge.
Discipline ≠ infrastructure.
```

We run a $2.4k/year stack because we believe **the audit trail is the moat** — and that can be built on plain text and free tools. Scale the stack when the track record earns it.

🃏⚔️
