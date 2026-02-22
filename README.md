# 👋 Hey, I'm Plag
**DeFi Builder | Crypto Author | Base, Plasma, BOB & Bittensor Ecosystem**

Building the future of decentralized finance on [Base](https://base.org) 🔵, [Plasma](https://plasma.to) ⚡, [BOB](https://gobob.xyz) 🟠, and [Bittensor](https://bittensor.com) 🟢

---

## 🚀 What I'm Building

### 🌐 [Spraay x402 Gateway](https://gateway.spraay.app)
An autonomous payment gateway on Base mainnet. AI agents pay USDC per request to access AI models, batch payments, and DeFi data. No API keys, no accounts — just HTTP + crypto.

- 🤖 200+ AI models via OpenAI-compatible API ($0.005/req)
- 💸 **Multi-stablecoin batch payments** — USDC, USDT, EURC, DAI via Spraay V3 ($0.01/req)
- 📊 Live swap quotes, token prices, balances, ENS resolution
- 🏪 Bazaar discoverable — agents find endpoints autonomously
- 🔗 Coinbase CDP facilitator on Base mainnet
- ⚡ Built on [x402 protocol](https://x402.org)
- 🤖 **MCP Server:** [spraay-x402-mcp](https://github.com/plagtech/spraay-x402-mcp) — plug into Claude Desktop or Cursor
- 📡 **11 paid + 6 free endpoints** | [Discovery →](https://gateway.spraay.app/.well-known/x402.json)

🔗 [Live →](https://gateway.spraay.app) | [GitHub →](https://github.com/plagtech/spraay-x402-gateway)

### 🤖 Spraay x402 MCP Server
**[github.com/plagtech/spraay-x402-mcp](https://github.com/plagtech/spraay-x402-mcp)**

MCP server for the Spraay x402 Gateway — connects Claude Desktop, Cursor, or any MCP-compatible AI client to onchain data, AI models, and batch payments on Base. 9 tools, pay-per-call in USDC.

| Tool | Cost | What It Does |
|------|------|--------------|
| `spraay_chat` | $0.005 | AI chat via 200+ models |
| `spraay_prices` | $0.002 | Live onchain token prices |
| `spraay_balances` | $0.002 | ETH + ERC-20 balances |
| `spraay_resolve` | $0.001 | ENS & Basename resolution |
| `spraay_batch_execute` | $0.01 | Batch USDC payments |
| `spraay_swap_quote` | $0.002 | Uniswap V3 swap quotes |
| + 3 more | $0.001+ | Models, tokens, gas estimates |

**Listed on:** [Smithery](https://smithery.ai) · [MCP.so](https://mcp.so) · [x402scan](https://x402scan.com) · [LobeHub MCP](https://lobehub.com/mcp)

### 💧 [Spraay](https://spraay.app)
Multi-chain batch payment protocol. Send to 200+ recipients in a single transaction.

- 🔵 **[Base](https://spraay.app)** — **V3: Multi-stablecoin** (USDC, USDT, EURC, DAI) + CCIP cross-chain ready
- 🟠 **[BOB](https://spraay.app/bob)** — Batch payments on Build on Bitcoin
- ⚡ **[Plasma](https://spraay.app/plasma)** — Batch XPL, USDT0 & ERC-20s with sub-second finality
- 🟣 **[Unichain](https://spraay.app/unichain)** — Batch payments on Unichain
- 🟢 **[Bittensor](https://spraay.app/tao)** — Native TAO batch transfers via `utility.batch_all` for subnet operators

**Features across chains:**
- ⚡ ~80% gas savings vs individual transfers
- 🪙 Multi-stablecoin support (USDC, USDT, EURC, DAI) on Base V3
- 💶 Competitive 0.25% fee on EURC (European stablecoin)
- 📊 Equal or variable amount distributions
- 📁 CSV import for large batches
- 🔗 Social handle resolution (Farcaster, ENS)
- 🏷️ Onchain memos & ERC-8004 agent attribution
- 💎 0.3% protocol fee (0.25% EURC)

**Contracts:**
| Chain | Contract | Version |
|-------|----------|---------|
| Base | [`0x3eFf0270...`](https://basescan.org/address/0x3eFf027045230A277293aC27bd571FBC729e0dcE) | V3 (multi-stablecoin + CCIP) |
| Base | [`0x16464...`](https://basescan.org/address/0x1646452F98E36A3c9Cfc3eDD8868221E207B5eEC) | V2 (legacy) |
| Unichain | [`0x08fA5D...`](https://uniscan.xyz/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | V2 |
| BOB | Deployed | V2 |
| Plasma | Deployed | V2 |
| Bittensor | spraay-tao | Native |

🔗 [spraay.app →](https://spraay.app)

### 📱 [Spraay Base App](https://spraay-base-dapp.vercel.app)
A standalone dapp on Base with batch payments and fiat onramp. Built with OnchainKit + ethers.js.

- 💸 Batch USDC payments on Base
- 💳 Coinbase Onramp — buy crypto directly in-app with fiat
- 🔗 Built with Next.js, OnchainKit, ethers.js v5

🔗 [Try it →](https://spraay-base-dapp.vercel.app) | [GitHub →](https://github.com/plagtech/spraay-base-app)

### 🥭 [MangoSwap](https://mangoswap.xyz)
A next-gen DEX on Base featuring instant swaps and scheduled trading with gas-free transactions.

- ⚡ Instant token swaps with best price execution
- ⏰ Recurring scheduled swaps (DCA made easy)
- ⛽ Gas-free trading via Coinbase Paymaster
- 📦 EIP-5792 transaction batching
- 🔄 Routes through Uniswap V3 & Aerodrome

🔗 [Try it now →](https://mangoswap.xyz) | [GitHub →](https://github.com/plagtech/mangoswap)

---

## 🤖 Agent Infrastructure
- **A2A Agent Card:** [agent.spraay.app](https://agent.spraay.app/.well-known/agent-card.json) — Google A2A protocol
- **XMTP Agent:** Agent Mango on production network
- **ERC-8004:** Registered agent identity on Ethereum mainnet
- **x402 Gateway:** 11 paid endpoints, Bazaar discoverable
- **MCP Server:** Listed on 4+ directories
- [Coinbase AgentKit PR #944](https://github.com/coinbase/agentkit/pull/944) — AI agents batch-send via Spraay
- [Bankr OpenClaw](https://bankr.bot) — Submitted Spraay skill for Bankr AI agent (69K+ users)

---

## 📚 Author
**"28 Tips for Creating Wealth in Crypto"**

Sharing insights and strategies from years of experience navigating the crypto markets since 2021.

---

## 🛠️ Tech Stack
```
Blockchain:    Solidity, Base, Ethereum, Plasma, Unichain, BOB, Bittensor (Substrate)
Frontend:      React, Next.js, TypeScript, TailwindCSS
Web3:          Wagmi, Viem, OnchainKit, ethers.js, RainbowKit
AI/Agents:     x402 Protocol, Coinbase AgentKit, ERC-8004, A2A, XMTP, MCP
DeFi:          Uniswap V3, Aerodrome, Chainlink CCIP
Backend:       Python, bittensor SDK, Express, OpenRouter
Infra:         Railway, Vercel, Fly.io, Coinbase CDP, Coinbase Paymaster
Tools:         EIP-5792, Coinbase Onramp, OpenZeppelin
```

---

## 🎯 Current Focus
- 🪙 Spraay V3 — multi-stablecoin batch payments live on Base
- 🌉 Chainlink CCIP cross-chain batch payments (coming soon)
- 🌐 Growing the Spraay x402 Gateway — AI agent infrastructure
- 🔨 Expanding Spraay multi-chain (Base, BOB, Plasma, Unichain, Bittensor)
- 🤖 AI agent integrations (AgentKit, Bankr, x402 Bazaar, A2A, XMTP)
- 📈 Growing Base, Plasma, BOB & Bittensor ecosystem presence
- 🤝 Building in the Base Build cohort

---

## 📊 GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=plagtech&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117)

---

## 🔗 Connect
[![Twitter](https://img.shields.io/badge/Spraay-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/spraay_app)
[![Twitter](https://img.shields.io/badge/MangoSwap-FF6B00?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/mngoswp)
[![Twitter](https://img.shields.io/badge/LostPoet-000000?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/lostpoet)
[![MangoSwap](https://img.shields.io/badge/MangoSwap-0052FF?style=for-the-badge&logo=ethereum&logoColor=white)](https://mangoswap.xyz)
[![Spraay](https://img.shields.io/badge/Spraay-8B0000?style=for-the-badge&logo=ethereum&logoColor=white)](https://spraay.app)
[![Farcaster](https://img.shields.io/badge/Farcaster-855DCD?style=for-the-badge&logo=farcaster&logoColor=white)](https://warpcast.com/plag)

---

<div align="center">
  <sub>Building on Base, Plasma, BOB & Bittensor 🔵⚡🟠🟢</sub>
</div>
