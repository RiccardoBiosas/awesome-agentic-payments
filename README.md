<p align="center">
  <a href="https://postimg.cc/bsMdChyg">
    <img src="https://i.postimg.cc/sgfS2jbk/image.png" alt="Agentic payments ecosystem" width="820">
  </a>
</p>

<h1 align="center">🤖💰 awesome-agentic-payments security</h1>

<p align="center">
  Curated intelligence on protocols, platforms, and safeguards for autonomous (agentic) payments across Web3 and AI ecosystems.
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Focus-Agentic%20Payments-5B8DEF?style=for-the-badge" alt="Focus: Agentic Payments"></a>
  <a href="#"><img src="https://img.shields.io/badge/Last%20Update-2026--04--19-success?style=for-the-badge" alt="Last update: 2026-04-19"></a>
  <a href="#-contribution"><img src="https://img.shields.io/badge/Contributions-Welcome-FF69B4?style=for-the-badge" alt="Contributions welcome"></a>
</p>

> Agent payments delegate intent, validation, and settlement to AI. This list tracks the standards, rails, and defenses that keep those autonomous transactions accountable.

---

## 📄 Standards and Protocols

The foundational specifications that enable AI agents to securely and programmatically send and receive payments.

| Standard / Protocol                              | Description                                                                                                                                                                                                                                                                                                                            |
| :----------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Agent Payments Protocol (AP2)**                | Open standard from Google that uses Verifiable Digital Credentials (VDCs) to capture cart intent, user consent, and payment method mandates. Guarantees integrity of the approval chain and supports fiat rails, stablecoins, and AP2-compliant providers such as Stripe, PayPal, and Coinbase.                                         |
| **Agentic Commerce Protocol (ACP)**              | Joint OpenAI × Stripe protocol that issues Shared Payment Tokens after the user authorizes a payment. Tokens are passed to merchants via API, enabling instant checkout flows inside ChatGPT and rapid integration with existing e-commerce systems.                                                                                   |
| **x402 Protocol**                                | Crypto-native extension of AP2 that reuses the HTTP `402 Payment Required` status code so agents can negotiate, request, and settle payments on-chain using stablecoins or other programmable assets.                                                                                                                                   |
| **Model Context Protocol (MCP)**                 | Interoperability layer that lets AI agents connect to external tools and data sources through a standardized, natural-language interface. Payment providers such as Stripe, Adyen, and Alipay are building MCP servers to expose commerce and reconciliation capabilities to agent ecosystems.                                         |
| **Trusted Agent Protocol (Visa)**                | Open-source specification from Visa for building trusted agent-to-agent payment workflows with verifiable identity, consent, and settlement guarantees.                                                                                                                                                                                 |

---

## 🛠️ Instruments & Platforms

Solutions and products that provide ready-to-use agentic payment capabilities.

- [Buy it in ChatGPT (OpenAI)](https://openai.com/index/buy-it-in-chatgpt/) — native commerce flow inside ChatGPT that lets users purchase digital and physical goods directly in the chat without manual API setup.
- [Shopify × OpenAI Commerce](https://www.shopify.com/news/shopify-open-ai-commerce) — Shopify's integration blueprint for enabling autonomous storefronts and conversational checkout experiences powered by agents.
- [OpenAI Instant Checkout](https://developers.openai.com/commerce/) — reference implementation of ACP that lets ChatGPT agents fulfill orders using Shared Payment Tokens while preserving merchant observability.
- [Mastercard Agent Pay](https://www.mastercard.com/us/en/business/artificial-intelligence/mastercard-agent-pay.html) — enterprise-grade agent payment fabric that enforces Know-Your-Agent (KYA) enrollment, policy controls, and auditability across corporate transaction flows.
- [PayPal Agent Payments](https://developer.paypal.com/community/blog/PayPal-Agent-Payments-Protocol/) — AP2-aligned gateway with biometric consent verification and additional fraud controls layered on PayPal's payments stack.
- [Kite Agentic Payments Platform](https://gokite.ai/) — infrastructure for orchestrating agent-driven payments, reconciliation, and treasury operations across fiat and crypto rails.
- **MCP Commerce Servers** — Stripe, Adyen, Alipay, and other PSPs are rolling out MCP adapters that expose catalog, inventory, and settlement actions so autonomous agents can transact through standardized toolchains.

---

## 📰 Articles & Research

Analyses, reports, and news covering the rise of agentic payments.

- [Google Cloud: Announcing AP2](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol) — deep dive into AP2 mandates (Cart, Intent, Payment) and how VDCs maintain an immutable consent chain for autonomous commerce.
- **Who Pays for You?** — overview of how agent payments shift responsibility for purchase decisions, highlighting the need for protocols that encode intent verification, accountability, and interpretability in autonomous commerce.
- [BCG: Stablecoins & Agentic AI Reshaping Payments](https://fintechnews.ch/payments/bcg-study-stablecoins-agentic-ai-instant-cross-border-transactions-among-top-trends-reshaping-payments/78499/) — consulting study on the macro trends driving autonomous, cross-border, and AI-mediated transactions.
- [Cloudflare: Secure Agentic Commerce](https://blog.cloudflare.com/secure-agentic-commerce/) — architectural guidance on protecting smart commerce agents at the edge, with policy enforcement and traffic shielding.
- [Shopify × OpenAI Announcement](https://www.shopify.com/news/shopify-open-ai-commerce) — outlines how merchants can embed AI-driven checkout experiences and what operational safeguards are required.
- [Coinbase × AP2 Stablecoin Partnership](https://www.binance.com/en/square/post/29798493296010) — details on extending AP2 to programmable stablecoin settlement and cross-border payouts.
- [TessPay: Verify-then-Pay Infrastructure for Trusted Agentic Commerce (arXiv:2602.00213)](https://arxiv.org/abs/2602.00213) — Goenka et al. argue that existing standards cover only fragments of the agent-commerce trust gap and propose a unified verify-then-pay lifecycle that binds task delegation, post-execution settlement with verifiable work evidence, and end-to-end audit mechanisms for dispute resolution.
- [Zero-Trust Runtime Verification for Agentic Payment Protocols (arXiv:2602.06345)](https://arxiv.org/abs/2602.06345) — Lan et al. analyze the AP2 mandate lifecycle under realistic agent runtime behavior (retries, concurrency, orchestration), surface replay and context-redirect gaps left by specification-level guarantees, and propose a runtime framework with explicit context binding and consume-once semantics that holds verification latency around 3.8 ms at up to 10,000 TPS.
- [Whispers of Wealth: Red-Teaming Google's Agent Payments Protocol via Prompt Injection (arXiv:2601.22569)](https://arxiv.org/abs/2601.22569) — Debi and Zhu red-team a functional AP2 shopping agent built on Gemini-2.5-Flash and the Google ADK, introducing the Branded Whisper Attack (product-ranking manipulation) and Vault Whisper Attack (sensitive data exfiltration) to show that AP2's cryptographic mandates do not, on their own, defeat indirect and direct prompt injection.

---

## 🔐 Security Solutions

Frameworks and products focused on safeguarding agent identities, transactions, and commerce workflows.

- [SailPoint Agent Identity Security](https://www.sailpoint.com/products/agent-identity-security) — identity governance controls to authenticate, authorize, and monitor AI agents in enterprise environments.
- [HUMAN Security Agentic Commerce Protection](https://www.humansecurity.com/platform/solutions/agentic-commerce/) — bot and fraud defense tailored to agent-driven purchasing experiences.
- [AgentDyn (SaFo-Lab)](https://github.com/SaFo-Lab/AgentDyn) — dynamic, open-ended benchmark for evaluating prompt injection attacks against real-world agent security systems, built on top of AgentDojo with 60 open-ended user tasks and 560 injection test cases. Ships with new `shopping`, `github`, and `dailylife` suites and inherits AgentDojo's `banking`, `slack`, `travel`, and `workspace` suites — making it directly usable for stress-testing agentic payment and banking workflows (e.g., transfer authorization, account queries) against indirect prompt injection. Supports defenses including `tool_filter`, `spotlighting_with_delimiting`, `piguard_detector`, and `prompt_guard_2_detector` out of the box.
- **Threat Landscape** — Core risks include prompt injection that manipulates payment parameters, agent impersonation of trusted personalities, and confused-deputy abuse of MCP servers. Mitigations rely on Zero Trust architectures, Attribute-Based Access Control (ABAC), runtime intent verification, and circuit breakers for cross-protocol calls.
- **Assurance Patterns** — Combine cryptographic mandates (AP2 VDCs, Shared Payment Tokens), Know-Your-Agent registries, and Zero-Knowledge Proofs to prove compliance without leaking sensitive data, while logging accountability trails for regulators and dispute resolution.

---

## 💡 Contribution

Know of a great agentic payment protocol, standard, platform, or resource that isn't listed here? We welcome your contributions!
