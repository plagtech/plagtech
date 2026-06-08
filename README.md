# 👋 Hey, I'm Plagtech
**DeFi Builder | Crypto Author | Multi-Chain Ecosystem**

Building the future of decentralized finance across 15 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧡🧠₿⚡💧⭐

---

## 🚀 What I'm Building

### 🌐 [Spraay x402 Gateway](https://gateway.spraay.app) — v3.8.1
A full-stack autonomous payment gateway live on **Base & Solana mainnet**. AI agents pay USDC per request to access DeFi, payments, AI inference, analytics, payroll, escrow, research, compute, and 200+ AI models. No API keys, no accounts — just HTTP + crypto.

- 📡 **157 primitives — 151 paid + 6 free across 39 categories** | [Discovery →](https://gateway.spraay.app/.well-known/x402.json)
- 🤖 **200+ AI models** — OpenAI-compatible chat completions via **BlockRun + OpenRouter** (streaming, function calling, vision)
- 🧬 **Bittensor decentralized inference** — censorship-resistant chat, image gen, and embeddings via SN64/SN19
- 💸 **Batch payments** — any ERC-20 token + native currency to 200 recipients, implementing **[BPA 1.0](https://docs.spraay.app/bpa/1.0/)** (Batch Payments for Agents)
- 🔗 Swap, bridge, payroll, invoicing, escrow, oracle, analytics, DeFi positions
- 🧠 On-chain inference — wallet classification, tx analysis, contract explanation, intelligence briefings
- ⚙️ **Managed Compute + Compute Futures** — text/image/video/TTS/STT/embeddings with prepaid credit tiers
- 🔍 **Search / RAG** — web search, content extraction, and question answering
- 📚 **Research & Reference (23 endpoints)** — academic papers, preprints, biomedical, chemistry, demographics
- 🏭 **Supply Chain (SCTP)** — suppliers, purchase orders, invoices, AI invoice verification
- 👛 **Agent Wallet** — ERC-4337 smart wallets with session keys & spending controls
- 📧 Email, SMS, XMTP messaging, webhooks, cron scheduling, IPFS/Arweave storage, multi-chain RPC, logs
- 🔐 KYC/sanctions screening, auth sessions, immutable audit trail, FIFO tax & IRS 8949 reports
- 🏪 **Bazaar discoverable** — agents find endpoints autonomously
- ⚡ **Dual protocol** — [x402](https://x402.org) (Coinbase CDP facilitator on Base) **+ MPP** (Tempo / stripe-spt / pathUSD)

🔗 [Live →](https://gateway.spraay.app) | [Docs →](https://docs.spraay.app) | [GitHub →](https://github.com/plagtech/spraay-x402-gateway)

### 🤖 Spraay x402 MCP Server
**[mcp.spraay.app](https://mcp.spraay.app) · [github.com/plagtech/spraay-x402-mcp](https://github.com/plagtech/spraay-x402-mcp)**

**153 tools** across 25+ categories — connects Claude Desktop, Cursor, or any MCP-compatible AI to full-stack DeFi infrastructure on Base & Solana. Pay USDC per call via x402 protocol. Supabase-backed persistent storage.

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

**Categories:** AI · Bittensor · Payments · Swap · Bridge · Oracle · Payroll · Invoice · Escrow · Analytics · On-chain Inference · Managed Compute · Compute Futures · Search/RAG · Research · Communication · Infrastructure · Identity & Access · Compliance · GPU · Supply Chain (SCTP) · Agent Wallet · RTP

**Listed on:** [Smithery](https://smithery.ai/server/@plagtech/spraay-x402-mcp) · [Official MCP Registry](https://github.com/modelcontextprotocol/servers) · [Glama](https://glama.ai/mcp/servers/@plagtech/spraay-x402-mcp) · [PulseMCP](https://pulsemcp.com) · [mcp.spraay.app](https://mcp.spraay.app)

### 💧 [Spraay](https://spraay.app)
Multi-chain batch payment protocol — live on **15 chains**. Send any ERC-20 token or native currency to 200+ recipients in a single transaction. Open spec: **[BPA 1.0](https://docs.spraay.app/bpa/1.0/)**.

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
| 💧 [XRP Ledger](https://spraay.app/xrp) | x402 Gateway | XRP (native batch) |
| ⭐ [Stellar](https://spraay.app/stellar) | x402 Gateway | XLM (native batch) |

**Features:**
- ⚡ ~80% gas savings vs individual transfers
- 🪙 Supports any ERC-20/BEP-20/SPL token + native currency
- 📊 Equal or variable amount distributions
- 📁 CSV import for large batches
- 🔗 Social handle resolution (Farcaster, ENS, Basenames)
- 💎 0.3% protocol fee

🔗 [spraay.app →](https://spraay.app)

### 🤖 [Robot Task Protocol (RTP)](https://github.com/plagtech/rtp-spec)
Open standard for AI agents to hire robots via x402 USDC micropayments. 8 gateway endpoints live.

- 📐 [rtp-spec](https://github.com/plagtech/rtp-spec) — Protocol specification
- 🔧 [rtp-sdk](https://github.com/plagtech/rtp-sdk) — JavaScript SDK
- 🐍 [rtp-python-sdk](https://github.com/plagtech/rtp-python-sdk) — Python SDK (PyPI: `spraay-rtp`)
- 🍓 [rtp-pi-demo](https://github.com/plagtech/rtp-pi-demo) — Raspberry Pi 5 hardware demo
- 📡 [rtp-xmtp-mesh](https://github.com/plagtech/rtp-xmtp-mesh) — XMTP mesh network
- 🌟 [awesome-rtp](https://github.com/plagtech/awesome-rtp) — Curated resources

### 📱 [Spraay Base App](https://spraay-base-dapp.vercel.app)
Standalone dapp on Base with batch payments, Farcaster Mini App, and fiat onramp.

### 🥭 [MangoSwap](https://mangoswap.xyz)
DEX on Base with instant swaps and scheduled trading via gas-free transactions. Routes through Uniswap V3 & Aerodrome.

🔗 [Try it →](https://mangoswap.xyz) | [GitHub →](https://github.com/plagtech/mangoswap)

---

## 🤖 Agent Infrastructure

| Protocol | Details |
|----------|---------|
| **x402 Gateway** | 157 primitives (151 paid + 6 free), 39 categories, Bazaar discoverable, v3.8.1 — Base & Solana |
| **Dual Protocol** | x402 (Coinbase CDP facilitator) + MPP (Tempo / stripe-spt / pathUSD) |
| **BPA 1.0** | Batch Payments for Agents — open spec at [docs.spraay.app/bpa/1.0](https://docs.spraay.app/bpa/1.0/) |
| **MCP Server** | 153 tools, live at mcp.spraay.app |
| **Google ADK** | ✅ [Merged into google/adk-python-community](https://github.com/google/adk-python-community/pull/95) — first community tool |
| **Agent Wallet** | ERC-4337 smart wallets with session keys on Base mainnet |
| **A2A Agent Card** | [agent.spraay.app](https://agent.spraay.app/.well-known/agent-card.json) |
| **XMTP Agent** | Agent Mango on production network via Fly.io |
| **ERC-8004** | MangoSwap #26345, Spraay #26346, Dexter Agent #27567 |
| **Virtuals ACP** | Registered Provider on [agdp.io](https://agdp.io) — batch payments as a service |
| **RTP** | 8 endpoints, Robot Task Protocol for physical AI |
| **SCTP** | 8 endpoints, Supply Chain Trade Protocol |
| **OpenClaw Skill** | Published on ClawHub as `plagtech` |

**Ecosystem integrations:**
- [google/adk-python-community PR #95](https://github.com/google/adk-python-community/pull/95) ✅ merged — **first community tool in Google's Agent Development Kit**
- [AWS Strands PR #825](https://github.com/strands-agents/tools/pull/825) ✅ merged
- [coinbase/x402 ecosystem listing](https://github.com/coinbase/x402) ✅ merged
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ✅ merged
- [Block Goose](https://github.com/block/goose) ✅ merged
- [NVIDIA NeMo-Agent-Toolkit-Examples PR #20](https://github.com/NVIDIA/NeMo-Agent-Toolkit-Examples/pull/20) — open
- [Coinbase AgentKit PR #944](https://github.com/coinbase/agentkit/pull/944) — open
- [LangChain docs PR #3245](https://github.com/langchain-ai/docs/pull/3245) — open · `langchain-spraay` on PyPI
- [Solana Foundation pay-skills PR #97](https://github.com/solana-foundation/pay-skills/pull/97) — open
- [Bankr OpenClaw](https://bankr.bot) — deployed

---

## 📚 Author
**"28 Tips for Creating Wealth in Crypto"**

Insights and strategies from years navigating crypto markets since 2021

---

## 🛠️ Tech Stack
```
Blockchain:    Solidity, Clarity, Base, Ethereum, Arbitrum, Polygon, BNB Chain,
               Avalanche, Unichain, Plasma, BOB, Solana, Bittensor, Stacks, Bitcoin
Frontend:      React, Next.js, TypeScript, TailwindCSS
Web3:          Wagmi, Viem, OnchainKit, ethers.js, RainbowKit, Phantom,
               UniSat, Xverse, Leather
AI/Agents:     x402 Protocol, MPP, MCP, Google ADK, Coinbase AgentKit, ERC-8004,
               A2A, XMTP, BlockRun SDK, Bittensor, Virtuals ACP, Dexter,
               NVIDIA Agent Toolkit, RTP, SCTP, ProofLayer
DeFi:          Uniswap V3, Aerodrome
Backend:       Node.js, Express, Python, bittensor SDK
Database:      Supabase (Postgres)
Infra:         Railway, Vercel, Fly.io, Coinbase CDP, Coinbase Paymaster
Tools:         EIP-5792, EIP-4337, Coinbase Onramp, OpenZeppelin, OpenRouter, BlockRun
```

---

## 🎯 Current Focus
- 💧 Spraay x402 Gateway v3.8.1 — 157 primitives, dual protocol (x402 + MPP), Base & Solana
- 📐 BPA 1.0 — open Batch Payments for Agents spec
- 🤖 RTP — Robot Task Protocol for Physical AI + Base Batches 2026 Robotics Track
- 🏭 SCTP — Supply Chain Trade Protocol for B2B agent commerce
- 📈 Ecosystem grants (Arbitrum, Stacks, Agent Fund, and more)
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
  <sub>Building on 15 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧡🧠₿⚡💧⭐ · Integrated with Google ADK 🟢</sub>
</div>
