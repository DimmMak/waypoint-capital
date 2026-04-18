# 👀 Watchlist — Blue Hill Capital

> Tickers under active observation. Not positions — candidates.
> Run `.price` on this list any time. Re-rumble when curiosity strikes.

---

## Current watchlist (11 names)

| Ticker | Name | Sector |
|---|---|---|
| TSLA | Tesla | EV / AI / Robotics |
| NVDA | NVIDIA | AI silicon |
| AMD | Advanced Micro Devices | AI silicon (credible #2) |
| ORCL | Oracle | Enterprise software + AI infra |
| PLTR | Palantir | AI platform / agentic |
| MSFT | Microsoft | AI compounder (Mag7) |
| META | Meta Platforms | Social + AI |
| GOOG | Alphabet | Search + Cloud + AI |
| MU | Micron | Memory / HBM |
| CRM | Salesforce | Agentic AI / enterprise |
| BE | Bloom Energy | Fuel cells / AI power infra |

---

## 📊 Last snapshot — 2026-04-18 (end of day Fri)

| Ticker | Regular | Post-Mkt | Change % | Day Range |
|---|---|---|---|---|
| TSLA | $400.62 | $401.09 | +3.20% | $391.65 – $409.28 |
| NVDA | $201.68 | $200.96 | +1.91% | $199.27 – $201.70 |
| AMD | $278.39 | $277.25 | +0.37% | $274.14 – $281.05 |
| ORCL | $175.06 | $174.61 | **-2.31%** | $173.36 – $184.50 |
| PLTR | $146.39 | $146.46 | +2.59% | $143.30 – $148.28 |
| MSFT | $422.79 | $422.36 | +0.44% | $420.69 – $431.58 |
| META | $688.55 | $686.80 | +1.66% | $675.13 – $691.52 |
| GOOG | $339.40 | $338.55 | +1.77% | $333.29 – $339.98 |
| MU | $455.07 | $452.60 | +0.02% | $452.20 – $470.97 |
| CRM | $182.14 | $182.58 | +0.12% | $181.03 – $187.98 |
| BE | $207.86 | $207.06 | **-0.78%** | $200.23 – $215.69 |

**Source:** price-desk v0.1.1 (yfinance) · **Pulled:** 2026-04-18 04:28 UTC

---

## 🎯 Quick commands

```bash
# Full watchlist refresh
.price TSLA NVDA AMD ORCL PLTR MSFT META GOOG MU CRM BE

# Or copy from below and paste:
python3 ~/.claude/skills/price-desk/scripts/price.py TSLA NVDA AMD ORCL PLTR MSFT META GOOG MU CRM BE
```

---

## 🔄 Rules

1. **This list is a candidate pool — nothing on it is a position.**
2. To promote a ticker: `.rumble TICKER` → decide → document trade.
3. To remove a ticker: delete the row. Git history preserves it forever.
4. Refresh snapshot table **weekly at minimum**, always before a rumble on any name.

---

## 📜 History

- **2026-04-18** — Initial watchlist: 11 names spanning AI silicon, AI software, memory, and AI power infra.
