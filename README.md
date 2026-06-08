# 🤖💰 awesome-agentic-payments

A curated list of protocols, standards, platforms, and resources for building autonomous and machine-to-machine (agentic) payment solutions powered by Web3 and AI.

---

## 📄 Standards and Protocols

The foundational specifications that enable AI agents to securely and programmatically send and receive payments.

| Standard / Protocol               | Description                                                                                                                                                                                                                                                 |
| :-------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Agent Payments Protocol (AP2)** | A shared protocol developed to securely authenticate and authorize AI agent-initiated payments. Supports multiple payment types (cards, stablecoins, bank transfers) and extends Agent2Agent (A2A) and Model Context Protocol (MCP) to a unified framework. |
| **x402 Protocol**                 | A crypto-native extension of the AP2. It utilizes the HTTP `402 Payment Required` status code to enable agents to request and settle payments on-chain using stablecoins.                                                                                   |

---

## 🛠️ Tools and Infrastructure

| Tool | Description |
| :--- | :---------- |
| **[TWZRD Agent Intel](https://intel.twzrd.xyz)** | Trust scoring MCP server for Solana agent wallets. Verify agent identity and on-chain reputation before x402 micropayments. Free tools: score_agent, preflight_check; paid: get_trust_receipt (x402). |

---

## 💡 Contribution

Know of a great agentic payment protocol, standard, platform, or resource that isn't listed here? We welcome your contributions!
