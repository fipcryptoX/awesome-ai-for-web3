# Awesome AI for Web3 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, SDKs, APIs, and resources for building AI agents that interact with Web3 protocols.

---

## Contents

- [AI Agent Frameworks](#ai-agent-frameworks)
- [Claude & OpenClaw Skills](#claude--openclaw-skills)
- [Web3 SDKs for Agents](#web3-sdks-for-agents)
- [DeFi APIs & Data](#defi-apis--data)
- [On-Chain Data & Indexing](#on-chain-data--indexing)
- [Wallet & Account Abstraction](#wallet--account-abstraction)
- [Smart Contract Automation](#smart-contract-automation)
- [RPC & Node Providers](#rpc--node-providers)
- [MCP Servers for Web3](#mcp-servers-for-web3)
- [Related Awesome Lists](#related-awesome-lists)

---

## AI Agent Frameworks

Frameworks and platforms for building autonomous AI agents with Web3 capabilities.

- [ElizaOS/eliza](https://github.com/elizaOS/eliza) - Web3-native multi-agent OS with plugins for Solana, EVM, and Coinbase; integrates with Discord, Telegram, and Farcaster.
- [Coinbase AgentKit](https://github.com/coinbase/agentkit) - "Every AI agent deserves a wallet." 50+ on-chain actions across Base, ETH, and Solana with LangChain/Vercel AI adapters.
- [GOAT SDK](https://github.com/goat-sdk/goat) - 200+ financial tools across 15+ chains including EVM, Solana, Cosmos, and Starknet.
- [Brian AI Toolkit](https://github.com/brian-knows/langchain-toolkit) - Natural language to Web3 transactions using the Brian-8B LLM intent engine.
- [Fetch.ai uAgents](https://github.com/fetchai/uAgents) - Python agent framework that auto-registers agents on-chain via the Almanac smart contract.
- [Thirdweb AI](https://github.com/thirdweb-dev/ai) - Insight + Engine + Nebula platform with OpenAI, LangChain, and AgentKit adapters plus an MCP server.
- [Virtuals GAME Python SDK](https://github.com/game-by-virtuals/game-python) - Python SDK for the GAME agentic framework; supports autonomous multi-step planning with Agent, Worker, and Function primitives across Twitter, Telegram, and custom platforms.

---

## Claude & OpenClaw Skills

Installable skill modules that teach AI agents how to interact with Web3 protocols, compatible with Claude Code and OpenClaw agents.

- [CoinMarketCap Claude Skills](https://github.com/coinmarketcap-official/skills-for-ai-agents-by-CoinMarketCap) - MCP, x402 pay-per-request, and direct API skills covering prices, technical analysis, DEX data, exchange info, and global market metrics for Claude Code agents.
- [CoinMarketCap OpenClaw Skills](https://clawhub.ai/u/bryan-cmc) - CoinMarketCap crypto market data skills packaged for OpenClaw agents.
- [ETH Skills](https://ethskills.com/) - 16 skill modules covering gas, wallets, L2s, ERC standards, Foundry testing, DeFi composability, and The Graph integration. Each module is a URL an agent fetches.
- [Abstract Foundation Skills](https://github.com/Abstract-Foundation/abstract-skills) - 7 skill modules for Abstract chain (zkSync L2): network config, contract deployment, Abstract Global Wallet, Safe Multisig, and ERC-8004 on-chain agent identity.
- [MegaETH AI Developer Skills](https://github.com/0xBreadguy/megaeth-ai-developer-skills) - 17 skill modules teaching AI agents MegaETH-specific development: instant transaction receipts (EIP-7966), RPC batching, mini-block patterns, storage optimization, and ERC-7710 delegation.
- [Uniswap AI Skills](https://github.com/Uniswap/uniswap-ai) - Official Uniswap skills for coding agents: V4 hook development, swap integration, cooperative closing auction, liquidity planning, and viem/wagmi helpers.

---

## Web3 SDKs for Agents

SDKs for programmatic interaction with blockchains and DeFi protocols.

### TypeScript / JavaScript

- [viem](https://github.com/wevm/viem) - Lightweight (35kB) TypeScript-first EVM library with type-safe ABI inference; foundation of Wagmi.
- [ethers.js](https://github.com/ethers-io/ethers.js) - Mature JS/TS Ethereum library with separate wallet/provider abstraction and ENS support.
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - Audited Solidity standards (ERC-20, ERC-721, ERC-1155, access control).

### Python

- [web3.py](https://github.com/ethereum/web3.py) - Python Ethereum interface; essential for Python AI/ML pipelines.
- [Hyperliquid Python SDK](https://github.com/hyperliquid-dex/hyperliquid-python-sdk) - Production-ready Python SDK for programmatic trading on Hyperliquid perpetuals DEX with WebSocket streaming.

### DeFi Protocol SDKs

- [Pendle SDK Boros](https://github.com/pendle-finance/sdk-boros-public) - TypeScript SDK for Pendle yield trading with an explicit agent-based authorization model and bulk order management.
- [Aave Utilities](https://github.com/aave/aave-utilities) - JS SDK for Aave V3 with contract helpers and math utilities.

---

## DeFi APIs & Data

APIs for accessing DeFi, token, and portfolio data across chains.

- [Zerion API](https://zerion.io/api) - Unified REST API covering portfolio, NFTs, DeFi positions across 8,000+ protocols on 38+ chains with millisecond latency.
- [DeFiLlama API](https://api-docs.defillama.com/) - Free, open TVL, yield, and fee data for 2,000+ protocols; no API key required.
- [CoinGecko API](https://www.coingecko.com/en/api) - 18,000+ coins, 250+ chains, OHLCV data, and a `pycoingecko` Python SDK.
- [GoldRush by Covalent](https://goldrush.dev/) - 100+ chains, AI Agent SDK (TypeScript), MCP server, and Google Cloud Marketplace integration.
- [Nansen API](https://www.nansen.ai/) - 500M+ labeled wallets, Smart Money analytics, and MCP integration.
- [Dune Analytics](https://dune.com/docs/api/) - SQL-based on-chain queries, community dashboards, and API access.
- [Moralis](https://moralis.io/) - Enterprise NFT, ERC-20, and transaction APIs with Streams webhooks and an MCP server.

---

## On-Chain Data & Indexing

Tools for indexing, querying, and exploring blockchain data.

- [The Graph](https://github.com/graphprotocol/graph-node) - Decentralized indexing protocol with 195B+ queries/month; `graph-cli` and `graph-ts` for subgraph development.
- [Blockscout API](https://docs.blockscout.com/devs/apis) - Open-source block explorer API on 600+ networks; REST, RPC (Etherscan-compatible), GraphQL, and JSON-RPC; free with no API key required.

---

## Wallet & Account Abstraction

SDKs and tools for managing wallets and smart accounts for AI agents.

- [Safe Core SDK](https://github.com/safe-global/safe-core-sdk) - Protocol, API, Relay, and Types kits for ERC-4337 smart accounts with batch transactions and gasless paymasters.
- [permissionless.js](https://github.com/pimlicolabs/permissionless.js) - Thin viem wrapper for Safe, Kernel, and Biconomy smart accounts with bundler and paymaster support.
- [ZeroDev SDK](https://github.com/zerodevapp/sdk) - Widely used ERC-4337 toolkit with Privy integration for embedded wallets.
- [Biconomy SDK](https://github.com/bcnmy/biconomy-client-sdk) - Smart account, bundler, and paymaster client SDK.

---

## Smart Contract Automation

Tools for automating smart contract execution and off-chain logic.

- [Gelato Automate SDK](https://github.com/gelatodigital/automate-sdk) - "If This, Then That" for smart contracts; supports time, CRON, event, and block triggers; Web3 Functions for serverless off-chain logic.

---

## RPC & Node Providers

Node infrastructure and enhanced RPC APIs for agent development.

- [Alchemy](https://www.alchemy.com/) - Enhanced APIs for 30+ chains with 30M compute units/month on the free tier and AI code tools.
- [QuickNode](https://www.quicknode.com/) - ~86ms latency across 23+ chains with NFT APIs and 100K requests/day on the free tier.
- [Infura](https://www.infura.io/) - EVM network RPC with Decentralized Infrastructure Network (DIN) and deep MetaMask ecosystem integration.

---

## MCP Servers for Web3

Model Context Protocol (MCP) servers that expose Web3 data and actions to AI assistants.

- [CoinMarketCap MCP](https://coinmarketcap.com/api/mcp/) - 12 tools covering real-time prices, technical analysis (MACD, RSI, Fibonacci), on-chain metrics, trending narratives, and crypto news for 10,000+ cryptocurrencies.
- [Dune MCP](https://docs.dune.com/api-reference/agents/mcp) - SQL-powered blockchain analytics via MCP; agents can discover tables, write and execute queries, and generate visualizations across multiple chains in a single conversation.
- [GoldRush MCP](https://goldrush.dev/) - 100+ chain on-chain data via MCP.
- [Moralis MCP](https://moralis.io/) - 100+ endpoints across multiple chains via MCP.
- [The Graph MCP](https://github.com/kukapay/thegraph-mcp) - Indexed blockchain data via MCP.
- [Subgraph MCP Skills](https://github.com/PaulieB14/subgraph-mcp-skills) - Access to 15,000+ subgraphs via MCP.
- [Thirdweb MCP](https://github.com/thirdweb-dev/ai) - 2,000+ blockchain read/write operations via MCP.

---

## Related Awesome Lists

- [awesome-web3](https://github.com/ahmet/awesome-web3) - General Web3 developer resources.
- [awesome-account-abstraction](https://github.com/4337Mafia/awesome-account-abstraction) - ERC-4337 SDKs, bundlers, paymasters, and indexers.
- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - AI agent frameworks and platforms.
- [awesome-mcp-servers](https://github.com/habitoai/awesome-mcp-servers) - Curated MCP server list.

---

## Contributing

Contributions welcome. Please read the [contributing guidelines](CONTRIBUTING.md) first.

---

## License

[CC0](LICENSE)
