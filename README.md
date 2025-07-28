# 🚀 Blocky-Diora-420B

**The most agentic blockchain code model ever released.**  
Purpose-built for smart contract engineering, dApp workflows, DeFi, zk, and Web3 infrastructure — with long-context, 358-language support, and full agentic capabilities.

---<img width="1536" height="1024" alt="blocky-benchmark" src="https://github.com/user-attachments/assets/2331ce65-0981-4ade-ba0a-3c3c863b1e12" />


## ✨ Overview

**Blocky-Diora-420B** is a state-of-the-art, open Mixture-of-Experts code model designed to power agentic coding workflows across blockchain ecosystems. It supports over **358 programming languages**, with first-class performance in **Solidity**, **Vyper**, **Rust**, **Move**, and **Cairo**.

Whether you're writing a DAO, deploying L2 rollups, simulating transactions, or auditing a multi-contract protocol — Blocky is your decentralized copilot.

---

## 🔑 Key Features

### 🔗 Agentic Blockchain Coding
- Smart contract generation, refactoring & security checks
- Deep language support for Solidity, Cairo, Vyper, Rust, Move
- CLI agent compatibility with `forge`, `cast`, `solc`, `aptos`, `starknet`, etc.
- 358+ languages supported

### 🌐 On-Chain Agentic Tooling
- Browse and reason over blockchain explorers like Etherscan/SolanaFM
- RPC interaction for simulations, verifications, and live querying
- Multi-chain: EVM + non-EVM support

### 🧠 Long-Context Code Understanding
- Native context window: **256K tokens**
- Extendable to **1M tokens** with [Yarn](https://github.com/kohya-ss/yarn) for full repository-level analysis

### 📦 Ecosystem Tooling (Blocky CLI)
- Forked from Gemini Code, rebuilt for Web3 agents
- Agentic scripting: deployments, gas profiling, governance proposals, and more
- Full integration with dev environments, CI/CD, and contract monitors

---

## 📊 Model Details

| Attribute                 | Value                                 |
|--------------------------|---------------------------------------|
| **Model Name**           | `Blocky-Diora-420B`                   |
| **Type**                 | Causal Language Model (decoder-only)  |
| **Architecture**         | Mixture-of-Experts (MoE)              |
| **Total Parameters**     | 420B                                  |
| **Active Parameters**    | 35B per forward pass                  |
| **Layers**               | 62                                    |
| **Experts**              | 160 (8 active)                        |
| **Attention Heads (GQA)**| 96 (Q), 8 (KV)                        |
| **Context Length**       | 262,144 tokens (native), 1M (w/ Yarn) |
| **Mode**                 | Non-thinking mode (no `<think>` tags) |

---

## ⚒ Developer Integration

- ✅ **VSCode**, **Remix**, **JetBrains** supported  
- ✅ Works with `.sol`, `.rs`, `.ts`, `.py`, `.yaml`, `.move`, `.toml`, etc.  
- ✅ Plug into agentic dev stacks like:
  - `Lagent-Web3`
  - `ChainForge`
  - `Autonolas`
  - `AI-powered DEX bots`

---

## 🌍 Open & Blockchain-Native

Built for public good. From DeFi to DAOs, zkVMs to cross-chain oracles — Blocky-Diora is open-source and extensible for builders across the decentralized stack.

---

## 🧪 Pretraining at Blockchain Scale

Blocky-Diora-420B pushes pretraining boundaries to improve reasoning, code execution, and dev agent reliability.

### 📚 7.5 Trillion Tokens
- 70% high-quality code
- Emphasis on:
  - Smart contracts
  - Blockchain infra
  - Protocol specs (EIPs, whitepapers, Git repos)

### 📏 Ultra-Long Context
- Handles entire repo ingestion
- PR/commit history diffs
- DAO governance flow understanding

### 🧼 Smarter Synthetic Data
- Aggressively rewrites noisy source data
- Elevates agent performance in malformed, undocumented, and real-world code

---

## 🧰 Get Started

```bash
# Install Blocky CLI (agent wrapper for code workflows)
git clone https://github.com/blocky-ai/blocky-cli
cd blocky-cli
npm install
blocky init
