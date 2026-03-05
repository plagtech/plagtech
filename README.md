# 👋 Hey, I'm Plagtech
**DeFi Builder | Crypto Author | Multi-Chain Ecosystem**

Building the future of decentralized finance across 11 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧡🧠

---

## 🚀 What I'm Building

### 🌐 [Spraay x402 Gateway](https://gateway.spraay.app) — v3.0.0
A full-stack autonomous payment gateway on Base mainnet. AI agents pay USDC per request to access DeFi, payments, AI inference, analytics, payroll, escrow, and 200+ AI models. No API keys, no accounts — just HTTP + crypto.

- 🤖 200+ AI models via OpenAI-compatible API
- 💸 Batch payments — any ERC-20 token + native ETH via Spraay
- 🔗 Bridge, swap, payroll, invoicing, escrow, oracle, analytics
- 🧠 AI inference — wallet classification, tx analysis, contract explanation
- 🏪 Bazaar discoverable — agents find endpoints autonomously
- 🔗 Coinbase CDP facilitator on Base mainnet
- ⚡ Built on [x402 protocol](https://x402.org)
- 📡 **33 paid + 6 free endpoints** | [Discovery →](https://gateway.spraay.app/.well-known/x402.json)

🔗 [Live →](https://gateway.spraay.app) | [GitHub →](https://github.com/plagtech/spraay-x402-gateway)

### 🤖 Spraay x402 MCP Server — v3.1.0
**[mcp.spraay.app](https://mcp.spraay.app) · [github.com/plagtech/spraay-x402-mcp](https://github.com/plagtech/spraay-x402-mcp)**

33 tools across 11 categories — connects Claude Desktop, Cursor, or any MCP-compatible AI to full-stack DeFi infrastructure on Base. Pay USDC per call via x402 protocol.

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

**Categories:** AI · Payments · Swap · Oracle · Bridge · Payroll · Invoice · Analytics · Escrow · AI Inference · Data

**Listed on:** [Smithery](https://smithery.ai/servers/Plagtech/Spraay-x402-mcp) · [MCP.so](https://mcp.so) · [Glama](https://glama.ai/mcp/servers/@plagtech/spraay-x402-mcp) · [PulseMCP](https://pulsemcp.com) · [mcp.spraay.app](https://mcp.spraay.app)

### 💧 [Spraay](https://spraay.app)
Multi-chain batch payment protocol — live on **11 chains**. Send any ERC-20 token or native currency to 200+ recipients in a single transaction.

**Live Deployments:**

| Chain | Contract | Native + Token Support |
|-------|----------|----------------------|
| 🔵 [Base](https://spraay.app) | [`0x1646...B5eEC`](https://basescan.org/address/0x1646452F98E36A3c9Cfc3eDD8868221E207B5eEC) | ETH + Any ERC-20 |
| ⟠ [Ethereum](https://spraay.app/ethereum) | [`0x15E7...58b3`](https://etherscan.io/address/0x15E7aEDa45094DD2E9E746FcA1C726cAd7aE58b3) | ETH + Any ERC-20 |
| ⬡ [Arbitrum](https://spraay.app/arbitrum) | [`0x08fA...E073`](https://arbiscan.io/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | ETH + Any ERC-20 |
| 🟣 [Polygon](https://spraay.app/polygon) | [`0x6d24...D7ff`](https://polygonscan.com/address/0x6d2453ab7416c99aeDCA47CF552695be5789D7ff) | POL + Any ERC-20 |
| 🟡 [BNB Chain](https://spraay.app/bnb) | [`0x3093...95C1`](https://bscscan.com/address/0x3093a2951FB77b3beDfB8BA20De645F7413432C1) | BNB + Any BEP-20 |
| 🔺 [Avalanche](https://spraay.app/avalanche) | [`0x0613...A650`](https://snowtrace.io/address/0x0613800F110A5baF830d15944f4AD783F066A650) | AVAX + Any ERC-20 |
| 🦄 [Unichain](https://spraay.app/unichain) | [`0x08fA...E073`](https://uniscan.xyz/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | ETH + Any ERC-20 |
| 🟢 [Plasma](https://spraay.app/plasma) | [`0x08fA...E073`](https://plasmascan.to/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | XPL + Any ERC-20 |
| 🔶 [BOB](https://spraay.app/bob) | [`0xEc85...4973`](https://explorer.gobob.xyz/address/0xEc8599026AE70898391a71c96AA82d4840C2e973) | ETH + Any ERC-20 |
| 🧡 [Solana](https://spraay.app/solana) | TypeScript SDK | SOL + Any SPL Token |
| 🧠 [Bittensor](https://spraay.app/tao) | spraay-tao | TAO (native `utility.batch_all`) |

**Features:**
- ⚡ ~80% gas savings vs individual transfers
- 🪙 Supports any ERC-20/BEP-20/SPL token + native currency
- 📊 Equal or variable amount distributions
- 📁 CSV import for large batches
- 🔗 Social handle resolution (Farcaster, ENS, Basenames)
- 💎 0.3% protocol fee

🔗 [spraay.app →](https://spraay.app)

### 📱 [Spraay Base App](https://spraay-base-dapp.vercel.app)
Standalone dapp on Base with batch payments, Farcaster Mini App, and fiat onramp.

- 💸 Batch payments on Base (any ERC-20 + ETH)
- 💳 Coinbase Onramp — buy crypto directly in-app
- 📱 Farcaster Mini App compatible
- 🔗 Built with Next.js, OnchainKit, ethers.js v5

🔗 [Try it →](https://spraay-base-dapp.vercel.app) | [GitHub →](https://github.com/plagtech/spraay-base-app)

### 🥭 [MangoSwap](https://mangoswap.xyz)
DEX on Base with instant swaps and scheduled trading via gas-free transactions.

- ⚡ Instant token swaps with best price execution
- ⏰ Recurring scheduled swaps (DCA made easy)
- ⛽ Gas-free trading via Coinbase Paymaster
- 📦 EIP-5792 transaction batching
- 🔄 Routes through Uniswap V3 & Aerodrome

🔗 [Try it →](https://mangoswap.xyz) | [GitHub →](https://github.com/plagtech/mangoswap)

---

## 🤖 Agent Infrastructure

| Protocol | Details |
|----------|---------|
| **x402 Gateway** | 33 paid endpoints, Bazaar discoverable, v3.0.0 |
| **MCP Server** | 33 tools, v3.1.0, live at mcp.spraay.app |
| **A2A Agent Card** | [agent.spraay.app](https://agent.spraay.app/.well-known/agent-card.json) |
| **XMTP Agent** | Agent Mango on production network |
| **ERC-8004** | Registered agent identities on Ethereum mainnet (#26345, #26346) |
| **Solana Gateway** | [gateway-solana.spraay.app](https://gateway-solana.spraay.app) |

**Ecosystem integrations:**
- [coinbase/x402 ecosystem listing](https://github.com/coinbase/x402) ✅ merged
- [Coinbase AgentKit PR #944](https://github.com/coinbase/agentkit/pull/944) — open
- [LangChain Community PR #557](https://github.com/langchain-ai/langchain/pull/557) — open
- [ElizaOS PR #274](https://github.com/elizaos/eliza/pull/274) — open
- [CrewAI PR #314](https://github.com/crewAIInc/crewAI/pull/314) — open
- [Block Goose PR #7525](https://github.com/block/goose/pull/7525) — open
- [smolagents/Hugging Face PR #1997](https://github.com/huggingface/smolagents/pull/1997) — open
- [Bankr OpenClaw](https://bankr.bot) — open

---

## 📚 Author
**"28 Tips for Creating Wealth in Crypto"**

Insights and strategies from years navigating crypto markets since 2021, including a chapter on liquidity cycles vs. the 4-year halving myth.

---

## 🛠️ Tech Stack
```
Blockchain:    Solidity, Base, Ethereum, Arbitrum, Polygon, BNB Chain,
               Avalanche, Unichain, Plasma, BOB, Solana, Bittensor
Frontend:      React, Next.js, TypeScript, TailwindCSS
Web3:          Wagmi, Viem, OnchainKit, ethers.js, RainbowKit, Phantom
AI/Agents:     x402 Protocol, MCP, Coinbase AgentKit, ERC-8004, A2A, XMTP
DeFi:          Uniswap V3, Aerodrome
Backend:       Node.js, Express, Python, bittensor SDK
Infra:         Railway, Vercel, Fly.io, Coinbase CDP, Coinbase Paymaster
Tools:         EIP-5792, Coinbase Onramp, OpenZeppelin, OpenRouter
```

---

## 🎯 Current Focus
- 💧 Spraay x402 Gateway v3.0.0 — 33 endpoints live, expanding to 57
- 🤖 MCP server v3.1.0 — 33 tools, live at mcp.spraay.app
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
[![MangoSwap](https://img.shields.io/badge/MangoSwap-0052FF?style=for-the-badge&logo=ethereum&logoColor=white)](https://mangoswap.xyz)
[![Spraay](https://img.shields.io/badge/Spraay-8B0000?style=for-the-badge&logo=ethereum&logoColor=white)](https://spraay.app)

---

<div align="center">
  <sub>Building on 11 chains 🔵⟠⬡🟣🟡🔺🦄🟢🔶🧡🧠</sub>
</div>
