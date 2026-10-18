# Trading / Market-AI

This lane contains AI-assisted market evidence systems and operator tooling. It is intentionally framed as evidence, proof, and audit tooling — not as guaranteed autonomous trading.

## Active structure

| repo | status | role |
|---|---|---|
| `project-umbrela` | core | Trading/market cockpit UI. Reads local snapshot data and displays HOT CEX candidates, proof windows, and audit links. |
| `worm-trading-agent` | active | Future execution/observability backend. Live execution remains disabled until proof gates and controls are formalized. |

## Research archive

| repo | status | role |
|---|---|---|
| `worm-magotshtora` | archive | Legacy AI trading terminal / regime-overseer research. |
| `worm-sa21magot` | archive | Prediction-market pilot and negative-edge autopsy. |
| `binance-sniper` | archive | Binance Desk (Rust desktop) + engine-rs paper engine. Real-order path is user-activated only; research results reported as-is, including negatives. |
| `lighter-live-desk` | archive | Local BTC perpetual desk: engine, dashboard API, Vite frontend. Observe-only by default; mainnet orders untested. |
| `sniperfx-mt5` | archive | MQL5 trend-continuation EA + read-only Alpha Lab. Ships `InpTradingEnabled=false`. |
| `lldesk-profile-capture` | archive | py-spy/bpftrace profiling sandbox for the desk; dummy-only, production path disabled. |

## Engine note

The current scanner/proof engine lives locally at `~/brutal1000_scanner`. Recommended future repo: `project-umbrela-engine` (private), only after a complete sensitive-material scan and cleanup.
