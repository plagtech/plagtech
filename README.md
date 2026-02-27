# 👋 Hey, I'm Plag
**DeFi Builder | Crypto Author | Multi-Chain Ecosystem**

Building the future of decentralized finance across 10 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧠

---

## 🚀 What I'm Building

### 🌐 [Spraay x402 Gateway](https://gateway.spraay.app)
An autonomous payment gateway on Base mainnet. AI agents pay USDC per request to access AI models, batch payments, and DeFi data. No API keys, no accounts — just HTTP + crypto.

- 🤖 200+ AI models via OpenAI-compatible API ($0.005/req)
- 💸 **Batch payments** — any ERC-20 token + native ETH via Spraay ($0.01/req)
- 📊 Live swap quotes, token prices, balances, ENS resolution
- 🏪 Bazaar discoverable — agents find endpoints autonomously
- 🔗 Coinbase CDP facilitator on Base mainnet
- ⚡ Built on [x402 protocol](https://x402.org)
- 🤖 **MCP Server:** [spraay-x402-mcp](https://github.com/plagtech/spraay-x402-mcp) — plug into Claude Desktop or Cursor
- 📡 **9 paid + 5 free endpoints** | [Discovery →](https://gateway.spraay.app/.well-known/x402.json)

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
| `spraay_batch_execute` | $0.01 | Batch payments (any ERC-20 + ETH) |
| `spraay_swap_quote` | $0.002 | Uniswap V3 swap quotes |
| + 3 more | $0.001+ | Models, tokens, gas estimates |

**Listed on:** [Smithery](https://smithery.ai) · [MCP.so](https://mcp.so) · [x402scan](https://x402scan.com) · [LobeHub MCP](https://lobehub.com/mcp) · [Glama](https://glama.ai/mcp/servers/@plagtech/spraay-x402-mcp)

### 💧 [Spraay](https://spraay.app)
Multi-chain batch payment protocol — live on **10 chains**. Send any ERC-20 token or native currency to 200+ recipients in a single transaction.

**Live Deployments:**

| Chain | Contract | Native + Token Support |
|-------|----------|----------------------|
| 🔵 [Base](https://spraay.app) | [`0x1646...B5eEC`](https://basescan.org/address/0x1646452F98E36A3c9Cfc3eDD8868221E207B5eEC) | ETH + Any ERC-20 |
| ⟠ [Ethereum](https://spraay.app/ethereum) | [`0x1646...B5eEC`](https://etherscan.io/address/0x1646452F98E36A3c9Cfc3eDD8868221E207B5eEC) | ETH + Any ERC-20 |
| ⬡ [Arbitrum](https://spraay.app/arbitrum) | [`0x08fA...E073`](https://arbiscan.io/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | ETH + Any ERC-20 |
| 🟣 [Polygon](https://spraay.app/polygon) | [`0x6d24...D7ff`](https://polygonscan.com/address/0x6d2453ab7416c99aeDCA47CF552695be5789D7ff) | POL + Any ERC-20 |
| 🟡 [BNB Chain](https://spraay.app/bnb) | [`0x3093...95C1`](https://bscscan.com/address/0x3093a2951FB77b3beDfB8BA20De645F7413432C1) | BNB + Any BEP-20 |
| 🔺 [Avalanche](https://spraay.app/avalanche) | [`0x0613...A650`](https://snowtrace.io/address/0x0613800F110A5baF830d15944f4AD783F066A650) | AVAX + Any ERC-20 |
| 🦄 [Unichain](https://spraay.app/unichain) | [`0x08fA...E073`](https://uniscan.xyz/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | ETH + Any ERC-20 |
| 🟢 [Plasma](https://spraay.app/plasma) | [`0x08fA...E073`](https://plasmascan.to/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | XPL + Any ERC-20 |
| 🔶 [BOB](https://spraay.app/bob) | [`0xEc85...4973`](https://explorer.gobob.xyz/address/0xEc8599026AE70898391a71c96AA82d4840C2e973) | ETH + Any ERC-20 |
| 🧠 [Bittensor](https://spraay.app/tao) | spraay-tao | TAO (native `utility.batch_all`) |

**Features across chains:**
- ⚡ ~80% gas savings vs individual transfers
- 🪙 Supports any ERC-20/BEP-20 token + native currency
- 📊 Equal or variable amount distributions
- 📁 CSV import for large batches
- 🔗 Social handle resolution (Farcaster, ENS)
- 💎 0.3% protocol fee

🔗 [spraay.app →](https://spraay.app)

### 📱 [Spraay Base App](https://spraay-base-dapp.vercel.app)
A standalone dapp on Base with batch payments and fiat onramp. Built with OnchainKit + ethers.js.

- 💸 Batch payments on Base (any ERC-20 + ETH)
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
- **x402 Gateway:** 9 paid endpoints, Bazaar discoverable
- **MCP Server:** Listed on 5+ directories
- [Coinbase AgentKit PR #944](https://github.com/coinbase/agentkit/pull/944) — AI agents batch-send via Spraay
- [Bankr OpenClaw](https://bankr.bot) — Submitted Spraay skill for Bankr AI agent (69K+ users)
- [Block Goose PR #7525](https://github.com/block/goose/pull/7525) — Spraay MCP extension tutorial

---

## 📚 Author
**"28 Tips for Creating Wealth in Crypto"**

Sharing insights and strategies from years of experience navigating the crypto markets since 2021.

---

## 🛠️ Tech Stack
```
Blockchain:    Solidity, Base, Ethereum, Arbitrum, Polygon, BNB Chain,
               Avalanche, Unichain, Plasma, BOB, Bittensor (Substrate)
Frontend:      React, Next.js, TypeScript, TailwindCSS
Web3:          Wagmi, Viem, OnchainKit, ethers.js, RainbowKit
AI/Agents:     x402 Protocol, Coinbase AgentKit, ERC-8004, A2A, XMTP, MCP
DeFi:          Uniswap V3, Aerodrome
Backend:       Python, bittensor SDK, Express, OpenRouter
Infra:         Railway, Vercel, Fly.io, Coinbase CDP, Coinbase Paymaster
Tools:         EIP-5792, Coinbase Onramp, OpenZeppelin
```

---

## 🎯 Current Focus
- 💧 Spraay — batch payments live on 10 chains
- 🌐 Growing the Spraay x402 Gateway — AI agent infrastructure
- 🤖 AI agent integrations (AgentKit, Bankr, x402 Bazaar, A2A, XMTP, Goose)
- 📈 Expanding MCP server distribution across directories
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
  <sub>Building on 10 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧠</sub>
</div>
