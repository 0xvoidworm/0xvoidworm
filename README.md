```text
╭───────────────────────────────────────────────────────────────╮
│   0 x v o i d w o r m                                         │
│   [INDEX] operator repository index — tiga lane                │
╰───────────────────────────────────────────────────────────────╯
```

Operator repository index split into three lanes: **Trading / Market-AI**, **Cyber / Security**, and **Infra / Operator / Shared**.

Positioning:

- **Trading lane** = AI-assisted market evidence and operator systems. It is not an “AI auto-trader that guarantees profit”. The lane emphasizes proof windows, paper evidence, disabled-live controls, and auditability.
- **Cyber lane** = separate lab/security tooling. It is not mixed into the market thesis.
- **Infra lane** = shared operator utilities, pages, profile, configuration, and supporting tools.

## Trading / Market-AI

| repo | status | role |
|---|---|---|
| [project-umbrela](https://github.com/0xvoidworm/project-umbrela) | `core` | Sober operator cockpit/UI for local market evidence, proof windows, and HOT CEX review. |
| [worm-trading-agent](https://github.com/0xvoidworm/worm-trading-agent) | `active` | Future execution/observability backend; live execution remains disabled until proof and controls are formalized. |
| [worm-magotshtora](https://github.com/0xvoidworm/worm-magotshtora) | `archive` | Legacy AI trading terminal / regime-overseer research. |
| [worm-sa21magot](https://github.com/0xvoidworm/worm-sa21magot) | `archive` | Prediction-market pilot and negative-edge autopsy. |
| [binance-sniper](https://github.com/0xvoidworm/binance-sniper) | `archive` | Binance Desk (Rust desktop) + engine-rs paper engine; real orders only by explicit user activation. |
| [lighter-live-desk](https://github.com/0xvoidworm/lighter-live-desk) | `archive` | Local BTC perpetual desk: engine, dashboard API, Vite frontend — observe-only by default. |
| [sniperfx-mt5](https://github.com/0xvoidworm/sniperfx-mt5) | `archive` | MQL5 trend-continuation EA + Alpha Lab; `InpTradingEnabled=false` baseline. |
| [lldesk-profile-capture](https://github.com/0xvoidworm/lldesk-profile-capture) | `archive` | py-spy/bpftrace profiling sandbox for the desk — dummy-only, production path disabled. |

See [`docs/trading.md`](docs/trading.md).

## Cyber / Security

| repo | status | role |
|---|---|---|
| [worm-grasiax](https://github.com/0xvoidworm/worm-grasiax) | `core` | Pentest toolkit / Claude-direct killchain operations. |
| [worm-venice-agent](https://github.com/0xvoidworm/worm-venice-agent) | `hibernate` | F4WORM purple-team operator codebase, currently hibernated. |
| [red-notes](https://github.com/0xvoidworm/red-notes) | `active` | Offensive security cheatsheets and methodology notes. |
| [worm-magotarena](https://github.com/0xvoidworm/worm-magotarena) | `deprecated` | Historical Win11 pentest distro scaffold. |
| [codex-nexus](https://github.com/0xvoidworm/codex-nexus) | `core` | Local operation console + exploit lab harness (private): drivers, targets, jobs, MCP server. |

See [`docs/cyber.md`](docs/cyber.md).

## Infra / Operator / Shared

| repo | status | role |
|---|---|---|
| [worm-search](https://github.com/0xvoidworm/worm-search) | `core` | Operator newtab / launcher / control-plane. |
| [worm-mistral-cli](https://github.com/0xvoidworm/worm-mistral-cli) | `utility` | Mistral/LLM CLI utility. |
| [worm-tiktok-bot](https://github.com/0xvoidworm/worm-tiktok-bot) | `utility` | Content/Telegram utility bot. |
| [dotfiles](https://github.com/0xvoidworm/dotfiles) | `active` | Hardened WSL2/offsec environment configuration. |
| [worm-homedir-vault](https://github.com/0xvoidworm/worm-homedir-vault) | `utility` | Encrypted home-directory backup vault. |
| [0xvoidworm.github.io](https://github.com/0xvoidworm/0xvoidworm.github.io) | `active` | Public writeups and GitHub Pages index. |
| [0xvoidworm](https://github.com/0xvoidworm/0xvoidworm) | `core` | This profile README and repository index. |
| [rust-workbench](https://github.com/0xvoidworm/rust-workbench) | `core` | Local Rust workbench: project generator, checks, coverage, version inventory. |
| [rust-ready-smoke](https://github.com/0xvoidworm/rust-ready-smoke) | `utility` | Minimal Rust template with a CI-ready pipeline (1.98.1, edition 2024). |
| [youtube-rust](https://github.com/0xvoidworm/youtube-rust) | `active` | Local YouTube pipeline: metadata, transcripts (local ASR) and timestamped frames. |
| [desktop-guard](https://github.com/0xvoidworm/desktop-guard) | `active` | Windows desktop that keeps only the shortcuts you allow. |
| [codex-operational-baseline](https://github.com/0xvoidworm/codex-operational-baseline) | `core` | Local operational baseline (private): inventory, doctor checks, environment ledger. |
| [Concat](https://github.com/0xvoidworm/Concat) | `utility` | Fork of jub0t/Concat — upstream fixes merged (#380 AppImage X11 crash, #396 VFR proxy rate) and Indonesian localisation (#404). |

See [`docs/infra.md`](docs/infra.md).

## Canonical taxonomy

The current classification convention is documented in [`docs/repo-taxonomy.md`](docs/repo-taxonomy.md):

- exactly one lane topic: `lane-trading`, `lane-cyber`, or `lane-infra`
- one status topic: `status-core`, `status-active`, `status-archive`, `status-hibernate`, `status-utility`, or `status-deprecated`
- theme topics describe the role without changing lane/status

No repository renames, visibility changes, deletes, or GitHub archive actions are implied by this index.
