# Poseidon — Public Audit Trail

Tech / AI growth equities · forward paper test from **2026-04-19** · review **2026-10-19** (6 months min).

**0 client capital deployed.** All snapshots below are forward paper test on real-time market data with frozen parameters.

## What you find here

| File | Purpose |
|---|---|
| `<date>_integrity.json` | SHA256 hashes of all frozen strategy files. Proves the engine hasn't been changed. |
| `<date>_drift_report.json` | Aggregate performance (NAV, return, drift vs backtest expected). No tickers. |
| `<date>_paper_state.json` | NAV + closed trade history (ticker / dates / prices / P&L). Open positions: count only. |

## What is NEVER published here

- Strategy parameters (slots, momentum window, regime breadth, rebalance freq)
- Selection signals or scoring formula thresholds
- Open position tickers (Pro+ subscribers only on https://thefrenchinvestor.com)

## Reference claims (source: ~/stoika/shared/claims_sheet.md)

- Backtest 11.3y (2015-04 → 2026-04) : CAGR +38.58% · Sharpe 1.21 · MaxDD -29.76%
- Live expected (Harvey-Liu 2015 + 7-factor audit, discount 0.85) : CAGR **26-29%** · Sharpe **0.80-0.92**
- DSR (Bailey-de Prado 2014) : 0.971
- Walk-forward 6 folds : 5/6 GREEN

## Disclaimer

Educational analytics tool. Not investment advice. Past performance does not guarantee future results. Forward paper test means no client capital is deployed; the strategy tracks real market data with frozen parameters for transparency.

---

## Snapshots index

| Date | NAV | Days live | Open | Closed | Frozen commit |
|---|---|---|---|---|---|
| 2026-04-26 | 1.0801 | 7 | 10 | 0 | `d26b89bad914` |
| 2026-04-28 | 1.0287 | 9 | 10 | 0 | `f3d5a67ab29a` |
| 2026-04-29 | 1.0278 | 10 | 10 | 0 | `4c2bcc510e67` |
| 2026-04-30 | 1.0213 | 11 | 10 | 0 | `4c2bcc510e67` |
| 2026-05-01 | 1.0484 | 12 | 10 | 0 | `4c2bcc510e67` |
| 2026-05-02 | 1.0427 | 13 | 10 | 0 | `4c2bcc510e67` |
| 2026-05-03 | 1.0427 | 14 | 10 | 0 | `beb86d3ed807` |
| 2026-05-04 | 1.0427 | 15 | 10 | 0 | `beb86d3ed807` |
| 2026-05-06 | 1.0427 | 17 | 10 | 0 | `fb4e26c7048f` |
| 2026-05-07 | 1.1073 | 18 | 10 | 0 | `fb4e26c7048f` |
| 2026-05-08 | 1.0427 | 19 | 10 | 0 | `fb4e26c7048f` |
| 2026-05-09 | 1.127 | 20 | 10 | 0 | `fb4e26c7048f` |
| 2026-05-10 | 1.127 | 21 | 10 | 0 | `fb4e26c7048f` |
