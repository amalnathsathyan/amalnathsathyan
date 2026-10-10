<div align="center">

```
 █████╗ ███╗   ███╗ █████╗ ██╗     ███╗   ██╗ █████╗ ████████╗██╗  ██╗
██╔══██╗████╗ ████║██╔══██╗██║     ████╗  ██║██╔══██╗╚══██╔══╝██║  ██║
███████║██╔████╔██║███████║██║     ██╔██╗ ██║███████║   ██║   ███████║
██╔══██║██║╚██╔╝██║██╔══██║██║     ██║╚██╗██║██╔══██║   ██║   ██╔══██║
██║  ██║██║ ╚═╝ ██║██║  ██║███████╗██║ ╚████║██║  ██║   ██║   ██║  ██║
╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝
```

<sub>🦉 &nbsp;night owl of defi · svm | evm · bangalore, in</sub>

<p>
  rust · anchor · pinocchio · solidity · typescript · turbin3 builder · defi mechanism nerd
</p>

> *"There are no two DLMM pools of the same pair at the same price."*
> <br/><sub>— the uncertainty principle of DLMMs, discovered while staring at pool dashboards</sub>

</div>

---

```rust
let amal = Builder {
    based_in:   "Bangalore, IN",
    chains:     ["Solana", "EVM"],
    writes:     ["Rust", "Anchor", "Pinocchio", "Solidity", "TypeScript"],
    obsessions: ["AMMs", "DLMMs", "perps", "flash loans", "liquidation math"],
    cohort:     "Turbin3 · Async Builders Q1-26",
    status:     Status::Shipping,
};
```

### defi & protocol design

| Project | Description | Tech |
|---------|-------------|------|
| [Magic Chess](https://github.com/amalnathsathyan/magic-chess) | Fully on-chain chess enforcing full FIDE rules, with gasless millisecond moves on ephemeral rollups and wagers in L1 escrow · [▶ play](https://arena.chessmagic.workers.dev) | Rust, Anchor, MagicBlock ER, Privy, Cloudflare Workers, Supabase |
| [Resonance](https://github.com/amalnathsathyan/resonance-dlmm-saros) | DLMM inter-pool arbitrage with mathematically optimised trade sizing and vault management | Rust, Anchor, TypeScript, Saros DLMM SDK, React |
| [DAMM v2 Fee Routing](https://github.com/amalnathsathyan/damm-v2-fee-routing) | PDA-owned zero-liquidity "honorary" positions on Meteora that accrue quote-only fees, routed to investors & creators | Rust, Anchor, Meteora CPI |
| [perps-lab](https://github.com/amalnathsathyan/perps-lab) | Perp DEX design lab built on Percolator risk math: oracles, vault invariants, funding, liquidations, JIT backstop capital | Rust, Pyth, Solana |
| [Lending Protocol](https://github.com/amalnathsathyan/anchor-lending-protocol) | Deposit, borrow, repay, withdraw & liquidate | Rust, Anchor |
| [OTC Swap](https://github.com/amalnathsathyan/otc-swap-solana) | One-to-many OTC swaps with escrowed offers, taker whitelists and platform fees | Rust, Anchor, TypeScript |
| [Quadratic Voting](https://github.com/amalnathsathyan/quadratic-voting) | DAOs, proposals and quadratic-weighted votes | Rust, Anchor |
| [Pinocchio Vault](https://github.com/amalnathsathyan/blueshift_pinocchio_vault) | Zero-dependency lamport vault with PDA-gated withdrawals | Rust, Pinocchio |
| [Turbin3 Q1-26](https://github.com/amalnathsathyan/tubin3-Q1-26) | Cohort proof-of-work: vault, escrow, AMM, NFT staking, MPL Core, dice game | Rust, Anchor |

### agents & automation

| Project | Description | Tech |
|---------|-------------|------|
| [JobsAgr](https://github.com/amalnathsathyan/jobsagr) | Autonomous agent that turns an X profile into structured job listings · [▶ live](https://jobsagr.vercel.app) | TypeScript, ElizaOS, DeepSeek R1 on Nosana, Playwright, Supabase |
| [EkoScout](https://github.com/amalnathsathyan/ekoscout) | Scans chains for hackathons, grants & jobs, ranked by opportunity vs. competition | TypeScript, Gemini, Cloud Run, Supabase, Cloudflare Pages |
| [Phantom Arb](https://github.com/amalnathsathyan/phantom-arb) | Autonomous AI arbitrage agent with scanner, execution engine and live dashboard | TypeScript, IronClaw, NEAR Intents |

### evm era

| Project | Description | Tech |
|---------|-------------|------|
| [OwlSwap](https://github.com/amalnathsathyan/OwlSwap) 🦉 | Flash-loan arbitrage between Uniswap V3 and TraderJoe on Arbitrum | Solidity, Aave V3, Hardhat |
| [AA Paymaster](https://github.com/amalnathsathyan/AA-PayMaster-ERC4337) | Paymaster that sponsors user gas under ERC-4337 account abstraction | Solidity, Hardhat |
| [ERC-6551](https://github.com/amalnathsathyan/erc6551) | Token-bound accounts: NFTs that own wallets | Solidity, Hardhat |
| [Reviral It](https://github.com/amalnathsathyan/ytweb3) | Community-governed video platform where lost videos compete to go viral again | Next.js, IPFS, Livepeer, GraphQL |
| [Message the Scammer](https://github.com/amalnathsathyan/send-a-messege-to-scammer) | Send an on-chain message from a drained wallet with gas paid by a fresh one | Solidity, ethers.js |

### rust & systems

| Project | Description | Tech |
|---------|-------------|------|
| [Gossip Glomers](https://github.com/amalnathsathyan/rust-distributed-system-challenges) | Fly.io distributed systems challenges, tested against Jepsen's Maelstrom *(in progress)* | Rust, Maelstrom |
| [Rust Lessons](https://github.com/amalnathsathyan/rust-lessons) | Beginner-friendly Rust exercises for blockchain devs | Rust |
| [Rust Fullstack](https://github.com/amalnathsathyan/rust-fullstack) | Small Rust tools: file compression, CryptoRank API client | Rust |

---

### open source contributions

| Project | PR |
|---------|-----|
| [moka-trade-labs/moka-trade](https://github.com/moka-trade-labs/moka-trade) | [Trades via TradeNoCpi and TradeCpi, with source-verified economics](https://github.com/moka-trade-labs/moka-trade/pull/38) |
| [moka-trade-labs/moka-trade](https://github.com/moka-trade-labs/moka-trade) | [Portfolio lifecycle with per-step reconciliation](https://github.com/moka-trade-labs/moka-trade/pull/37) |
| [moka-trade-labs/moka-trade](https://github.com/moka-trade-labs/moka-trade) | [Phase 1 tooling + CI, and Phase 2 LiteSVM harness](https://github.com/moka-trade-labs/moka-trade/pull/36) |
| [moka-trade-labs/moka-trade](https://github.com/moka-trade-labs/moka-trade) | [MVP planning: upstream pin, decisions, phased roadmap, oracle design](https://github.com/moka-trade-labs/moka-trade/pull/1) |
| [Allen-Saji/talos](https://github.com/Allen-Saji/talos) | [feat(mcp-host): multi-server orchestrator with namespaced tools](https://github.com/Allen-Saji/talos/pull/22) |
| [Allen-Saji/talos](https://github.com/Allen-Saji/talos) | [feat(channels): telegram bot adapter](https://github.com/Allen-Saji/talos/pull/38) |
| [Metlev-Labs/metlev-engine](https://github.com/Metlev-Labs/metlev-engine) | [feat: add surfpool runbook setup](https://github.com/Metlev-Labs/metlev-engine/pull/2) |
| [lfj-gg/joe-docs](https://github.com/lfj-gg/joe-docs) | [Fix missing `;` in swap-tokens docs](https://github.com/lfj-gg/joe-docs/pull/51) |

---

<div align="center">

[![Twitter](https://img.shields.io/badge/@amalnathsathyan-000000?style=flat&logo=x&logoColor=white)](https://twitter.com/amalnathsathyan)
[![LinkedIn](https://img.shields.io/badge/in%2Famalnathsathyan-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/amalnathsathyan)

<br/>

<i>every pool leaves just enough inefficiency. i come back for it.</i>
<br/>
<b>— amal</b> 🦉

</div>
