# 👋 Hey, I'm Plagtech
**DeFi Builder | Crypto Author | Multi-Chain Ecosystem**

Building the future of decentralized finance across 13 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧡🧠₿⚡

---

## 🚀 What I'm Building

### 🌐 [Spraay x402 Gateway](https://gateway.spraay.app) — v3.5.0
A full-stack autonomous payment gateway on Base mainnet. AI agents pay USDC per request to access DeFi, payments, AI inference, analytics, payroll, escrow, and 200+ AI models. No API keys, no accounts — just HTTP + crypto.

- 🤖 **93 AI models** — dual-provider inference via **BlockRun** (43 models, x402 wallet auth) + **OpenRouter** (50 models, API key)
- 🧠 **Smart routing** — `blockrun/auto` picks the cheapest capable model via ClawRouter (saves up to 78%)
- 💸 Batch payments — any ERC-20 token + native ETH via Spraay
- 🔗 Bridge, swap, payroll, invoicing, escrow, oracle, analytics
- 🧠 AI inference — wallet classification, tx analysis, contract explanation
- 📡 Email, XMTP messaging, webhooks, cron scheduling, IPFS storage, multi-chain RPC
- 🔐 KYC, auth sessions, audit trail, tax calculation — all with Supabase persistence
- 🏪 Bazaar discoverable — agents find endpoints autonomously
- 🔗 Coinbase CDP facilitator on Base mainnet
- ⚡ Built on [x402 protocol](https://x402.org)
- 📡 **76 paid + 11 free endpoints** | [Discovery →](https://gateway.spraay.app/.well-known/x402.json)

🔗 [Live →](https://gateway.spraay.app) | [Docs →](https://docs.spraay.app) | [GitHub →](https://github.com/plagtech/spraay-x402-gateway)

### 🤖 Spraay x402 MCP Server — v3.3.0
**[mcp.spraay.app](https://mcp.spraay.app) · [github.com/plagtech/spraay-x402-mcp](https://github.com/plagtech/spraay-x402-mcp)**

60+ tools across 16 categories — connects Claude Desktop, Cursor, or any MCP-compatible AI to full-stack DeFi infrastructure on Base. Pay USDC per call via x402 protocol. Supabase-backed persistent storage.

```json
{
  "mcpServers": {
    "spraay": {
      "command": "npx",
      "args": ["-y", "spraay-x402-mcp"],
      "env": { "EVM_PRIVATE_KEY": "0xYOUR_KEY" }
    }
  }
}
```

**Categories:** AI · Payments · Swap · Oracle · Bridge · Payroll · Invoice · Analytics · Escrow · AI Inference · Communication · Infrastructure · Identity & Access · Compliance · Data · Agent Wallet

**Listed on:** [Smithery](https://smithery.ai/servers/@plagtech/spraay-x402-mcp) · [Official MCP Registry](https://github.com/modelcontextprotocol/servers) · [Glama](https://glama.ai/mcp/servers/@plagtech/spraay-x402-mcp) · [PulseMCP](https://pulsemcp.com) · [mcp.spraay.app](https://mcp.spraay.app)

### 💧 [Spraay](https://spraay.app)
Multi-chain batch payment protocol — live on **13 chains**. Send any ERC-20 token or native currency to 200+ recipients in a single transaction.

**Live Deployments:**

| Chain | Contract | Native + Token Support |
|-------|----------|----------------------|
| 🔵 [Base](https://spraay.app) | [`0x1646...B5eEC`](https://basescan.org/address/0x1646452F98E36A3c9Cfc3eDD8868221E207B5eEC) | ETH + Any ERC-20 |
| ⟠ [Ethereum](https://spraay.app/ethereum) | [`0x15E7...58b3`](https://etherscan.io/address/0x15E7aEDa45094DD2E9E746FcA1C726cAd7aE58b3) | ETH + Any ERC-20 |
| ⬡ [Arbitrum](https://spraay.app/arbitrum) | [`0x5be4...4302`](https://arbiscan.io/address/0x5be43aA67804aD84fcb890d0AE5F257fb1674302) | ETH + Any ERC-20 |
| 🟣 [Polygon](https://spraay.app/polygon) | [`0x6d24...D7ff`](https://polygonscan.com/address/0x6d2453ab7416c99aeDCA47CF552695be5789D7ff) | POL + Any ERC-20 |
| 🟡 [BNB Chain](https://spraay.app/bnb) | [`0x3093...95C1`](https://bscscan.com/address/0x3093a2951FB77b3beDfB8BA20De645F7413432C1) | BNB + Any BEP-20 |
| 🔺 [Avalanche](https://spraay.app/avalanche) | [`0x0613...A650`](https://snowtrace.io/address/0x0613800F110A5baF830d15944f4AD783F066A650) | AVAX + Any ERC-20 |
| 🦄 [Unichain](https://spraay.app/unichain) | [`0x08fA...E073`](https://uniscan.xyz/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | ETH + Any ERC-20 |
| 🟢 [Plasma](https://spraay.app/plasma) | [`0x08fA...E073`](https://plasmascan.to/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | XPL + Any ERC-20 |
| 🔶 [BOB](https://spraay.app/bob) | [`0xEc85...4973`](https://explorer.gobob.xyz/address/0xEc8599026AE70898391a71c96AA82d4840C2e973) | ETH + Any ERC-20 |
| 🧡 [Solana](https://spraay.app/solana) | TypeScript SDK | SOL + Any SPL Token |
| 🧠 [Bittensor](https://spraay.app/tao) | spraay-tao | TAO (native `utility.batch_all`) |
| ⚡ [Stacks](https://spraay.app/stacks) | [`ST7431...spraay-batch`](https://explorer.stacks.co/txid/ST7431QK2YMPP3SQYJXZ3GTB6MJVGF07N2EV9R1F.spraay-batch) | STX (Clarity contract) |
| ₿ [Bitcoin](https://btc.spraay.app) | PSBT-based | BTC (UniSat/Xverse wallets) |

**Features:**
- ⚡ ~80% gas savings vs individual transfers
- 🪙 Supports any ERC-20/BEP-20/SPL token + native currency
- 📊 Equal or variable amount distributions
- 📁 CSV import for large batches
- 🔗 Social handle resolution (Farcaster, ENS, Basenames)
- 💎 0.3% protocol fee

🔗 [spraay.app →](https://spraay.app)

### 🤖 [Robot Task Protocol (RTP)](https://github.com/plagtech/rtp-spec)
Open standard for AI agents to hire robots via x402 USDC micropayments. 8 gateway endpoints live (Category 15).

- 📐 [rtp-spec](https://github.com/plagtech/rtp-spec) — Protocol specification
- 🔧 [rtp-sdk](https://github.com/plagtech/rtp-sdk) — JavaScript SDK
- 🐍 [rtp-python-sdk](https://github.com/plagtech/rtp-python-sdk) — Python SDK
- 🍓 [rtp-pi-demo](https://github.com/plagtech/rtp-pi-demo) — Raspberry Pi 5 hardware demo
- 📡 [rtp-xmtp-mesh](https://github.com/plagtech/rtp-xmtp-mesh) — XMTP mesh network
- 🌟 [awesome-rtp](https://github.com/plagtech/awesome-rtp) — Curated resources

### 🛡️ [ProofLayer](https://prooflayer.net)
Agent trust and reputation infrastructure. Multi-dimensional trust scores via EAS attestations on Base.

- 📦 npm SDK (`prooflayer-sdk`)
- 🌐 API at [api.prooflayer.net](https://api.prooflayer.net)
- 📊 Scoring: Financial 30% / Social 15% / Reliability 30% / Trust 25%

### 💰 [StablePay](https://stablepay.me)
Crypto payroll built on Spraay. Employer dashboard + recipient mobile app.

### 🌐 [Involver](https://involver.app)
Social network concept — Facebook-style + AOL topic rooms with crypto tipping via Base tokens.

### 📱 [Spraay Base App](https://spraay-base-dapp.vercel.app)
Standalone dapp on Base with batch payments, Farcaster Mini App, and fiat onramp.

### 🥭 [MangoSwap](https://mangoswap.xyz)
DEX on Base with instant swaps and scheduled trading via gas-free transactions. Routes through Uniswap V3 & Aerodrome.

🔗 [Try it →](https://mangoswap.xyz) | [GitHub →](https://github.com/plagtech/mangoswap)

---

## 🟢 NVIDIA Ecosystem Integration

Spraay is integrated across NVIDIA's autonomous agent stack announced at GTC 2026:

| NVIDIA Product | Integration | Status |
|---------------|-------------|--------|
| **OpenShell** | [Spraay sandbox](https://github.com/NVIDIA/OpenShell-Community/pull/50) — payment layer for autonomous agents | PR #50 |
| **NeMo Agent Toolkit** | [Crypto payments agent example](https://github.com/NVIDIA/NeMo-Agent-Toolkit-Examples/pull/20) — 8 async tools | PR #20 |
| **NemoClaw** | [Payment provider proposal](https://github.com/NVIDIA/NemoClaw/issues/625) — x402 integration design | Issue #625 |
| **Isaac GR00T** | RTP for robot task commissioning — agents hire GR00T-powered robots | Issue |
| **awesome-nemoclaw** | [Network policy preset](https://github.com/VoltAgent/awesome-nemoclaw/pull/1) — gateway egress rules | PR #1 |

---

## 🤖 Agent Infrastructure

| Protocol | Details |
|----------|---------|
| **x402 Gateway** | 76 paid + 11 free endpoints, Bazaar discoverable, v3.5.0 |
| **MCP Server** | 60+ tools, v3.3.0, live at mcp.spraay.app |
| **Agent Wallet** | Category 17 — managed wallets with session keys on Base mainnet |
| **A2A Agent Card** | [agent.spraay.app](https://agent.spraay.app/.well-known/agent-card.json) |
| **XMTP Agent** | Agent Mango on production network via Fly.io |
| **ERC-8004** | MangoSwap #26345, Spraay #26346, Dexter Agent #27567 |
| **Virtuals ACP** | Registered Provider on [agdp.io](https://agdp.io) — batch payments as a service |
| **RTP** | 8 endpoints, Robot Task Protocol for physical AI |
| **OpenClaw Skill** | Published on ClawHub as `plagtech` |

**Ecosystem integrations:**
- [coinbase/x402 ecosystem listing](https://github.com/coinbase/x402) ✅ merged
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ✅ merged
- [Block Goose PR #7525](https://github.com/block/goose/pull/7525) ✅ merged
- [NVIDIA OpenShell-Community PR #50](https://github.com/NVIDIA/OpenShell-Community/pull/50) — open
- [NVIDIA NeMo-Agent-Toolkit-Examples PR #20](https://github.com/NVIDIA/NeMo-Agent-Toolkit-Examples/pull/20) — open
- [NVIDIA NemoClaw Issue #625](https://github.com/NVIDIA/NemoClaw/issues/625) — open
- [VoltAgent awesome-nemoclaw PR #1](https://github.com/VoltAgent/awesome-nemoclaw/pull/1) — open
- [Coinbase AgentKit PR #944](https://github.com/coinbase/agentkit/pull/944) — open
- [LangChain Community PR #557](https://github.com/langchain-ai/langchain/pull/557) — open
- [ElizaOS PR #274](https://github.com/elizaos/eliza/pull/274) — open
- [CrewAI PR #314](https://github.com/crewAIInc/crewAI/pull/314) — open
- [smolagents/Hugging Face PR #1997](https://github.com/huggingface/smolagents/pull/1997) — open
- [Bankr OpenClaw](https://bankr.bot) — deployed

---

## 📚 Author
**"28 Tips for Creating Wealth in Crypto"** — pen name Brent Hamlin

Insights and strategies from years navigating crypto markets since 2021

---

## 🛠️ Tech Stack
```
Blockchain:    Solidity, Clarity, Base, Ethereum, Arbitrum, Polygon, BNB Chain,
               Avalanche, Unichain, Plasma, BOB, Solana, Bittensor, Stacks, Bitcoin
Frontend:      React, Next.js, TypeScript, TailwindCSS
Web3:          Wagmi, Viem, OnchainKit, ethers.js, RainbowKit, Phantom,
               UniSat, Xverse, Leather
AI/Agents:     x402 Protocol, MCP, Coinbase AgentKit, ERC-8004, A2A, XMTP,
               BlockRun SDK, Virtuals ACP, Dexter, NVIDIA Agent Toolkit,
               NVIDIA OpenShell, RTP, ProofLayer
DeFi:          Uniswap V3, Aerodrome
Backend:       Node.js, Express, Python, bittensor SDK
Database:      Supabase (Postgres)
Infra:         Railway, Vercel, Fly.io, Coinbase CDP, Coinbase Paymaster
Tools:         EIP-5792, Coinbase Onramp, OpenZeppelin, OpenRouter, BlockRun
```

---

## 🎯 Current Focus
- 💧 Spraay x402 Gateway v3.5.0 — 76 paid endpoints, Agent Wallet (Category 17), 13 chains
- 🟢 NVIDIA ecosystem — OpenShell sandbox, NeMo Agent Toolkit, NemoClaw, Isaac GR00T
- 🤖 RTP — Robot Task Protocol for Physical AI + Base Batches 2026 Robotics Track
- 🛡️ ProofLayer — agent trust scores + EAS attestations on Base
- 📈 Ecosystem grants (Arbitrum, Monad, Stacks, Agent Fund)
- 🤝 Building in the Base Build cohort

---

## 📊 GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=plagtech&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117)

---

## 🔗 Connect
[![Twitter](https://img.shields.io/badge/Spraay-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/spraay_app)
[![Twitter](https://img.shields.io/badge/MangoSwap-FF6B00?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/mngoswp)
[![Twitter](https://img.shields.io/badge/LostPoet-000000?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/lostpoet)
[![Farcaster](https://img.shields.io/badge/Farcaster-855DCD?style=for-the-badge&logo=farcaster&logoColor=white)](https://warpcast.com/plag)
[![Dev.to](https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/mr_hamlin)
[![MangoSwap](https://img.shields.io/badge/MangoSwap-0052FF?style=for-the-badge&logo=ethereum&logoColor=white)](https://mangoswap.xyz)
[![Spraay](https://img.shields.io/badge/Spraay-8B0000?style=for-the-badge&logo=ethereum&logoColor=white)](https://spraay.app)

---

<div align="center">
  <sub>Building on 13 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧡🧠₿⚡ · Integrated with NVIDIA's autonomous agent stack 🟢</sub>
</div>
