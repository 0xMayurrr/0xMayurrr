<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,50:161b22,100:0d1117&height=180&section=header&text=MAYUR%20P&fontSize=58&fontColor=00D9FF&desc=Web3%20Infrastructure%20Engineer%20%7C%20Distributed%20Systems%20%26%20Cryptography&descSize=18&descColor=8b949e&descAlignY=74&fontAlignY=42" width="100%"/>
</p>

<p align="center">
  <a href="https://mayurworks.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-mayurworks.vercel.app-00D9FF?style=flat-square&logo=vercel&logoColor=black&labelColor=ffffff"/></a>
  <a href="https://www.linkedin.com/in/mayurp03/"><img src="https://img.shields.io/badge/LinkedIn-mayurp03-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://x.com/0xMayurrr"><img src="https://img.shields.io/badge/X-@0xMayurrr-000000?style=flat-square&logo=x&logoColor=white"/></a>
  <a href="https://coderlegion.com/20276/beyond-identity-rethinking-trust-infrastructure-through-zero-knowledge-verification"><img src="https://img.shields.io/badge/Research-CoderLegion-2962FF?style=flat-square&logo=hashnode&logoColor=white"/></a>
  <a href="https://buildicy.com"><img src="https://img.shields.io/badge/Co--founder-Buildicy.com-00D9FF?style=flat-square&labelColor=161b22"/></a>
  <a href="mailto:mayurkarthick2006@gmail.com"><img src="https://img.shields.io/badge/Email-mayurkarthick2006%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=0xMayurrr&label=Telemetry%20Views&color=00D9FF&style=flat-square"/>
  <img src="https://img.shields.io/github/followers/0xMayurrr?label=Followers&style=flat-square&color=00D9FF"/>
</p>

---

### `$ cat engineering_profile.json`

```json
{
  "engineer": {
    "name": "Mayur P",
    "specialization": "Web3 Infrastructure & Cryptographic Protocols",
    "philosophy": "Don't build wrappers. Build the low-level caching, routing, and trust infrastructure underneath them.",
    "current_roles": [
      {
        "position": "Web3 SDE Intern",
        "focus": "Distributed consensus, backend optimization, and protocol integration"
      },
      {
        "position": "Co-founder & Technical Lead",
        "company": "Buildicy.com",
        "focus": "Custom blockchain client architecture, smart contract audits, and mentoring developers"
      }
    ],
    "core_competencies": {
      "distributed_systems": ["RPC proxies", "Sub-millisecond failover routing", "Load balancing"],
      "cryptography_identity": ["ZK-SNARKs", "W3C Decentralized Identifiers (DIDs)", "Verifiable credentials"],
      "smart_contracts": ["EVM factory-vault patterns", "Sui/Aptos Move resource modeling", "Security auditing"]
    }
  }
}
```

---

## 🏗️ Technical Leadership & Management

### **Co-founder & Technical Lead · [Buildicy](https://buildicy.com)**
*Building and scaling custom Web3 solutions for global clients while nurturing the next generation of engineers.*

*   **Engineering Delivery**: Architect and audit smart contracts, custom RPC setups, and decentralized integration layers for blockchain-related client applications.
*   **Developer Incubator**: Built and manage Buildicy's Web3 internship program from the ground up.
    *   Designed specialized training tracks covering EVM execution mechanics, ZK structures, and secure systems design.
    *   Mentor 10+ students, coordinating internal PR reviews, code standards, and agile sprint planning.
    *   Transitioned student developers from basic dApp prototyping to writing production-ready, gas-optimized, audited code.

---

## 🔬 Flagship Infrastructure — Production-Level Builds

### ⚙️ **RPCForge** — High-Availability Multi-Chain RPC Gateway
> **Production SaaS** · [rpcforge.dev](https://rpcforge.dev) · [Product Hunt Launch](https://www.producthunt.com/@0xmayurrr)

A self-hostable, multi-tenant RPC routing proxy designed as a high-performance alternative to centralized gateway services.
*   **Infrastructure**: Built a node-routing and caching layer supporting Ethereum, Polygon, BSC, and Arbitrum.
*   **Systems Engineering**: Implemented real-time token-bucket rate limiting, automatic sub-millisecond node failover, and telemetry analytics dashboard.
*   **Monetization**: Integrated Stripe billing for tiered subscription levels (Free → $9 → $29 → $99/mo).
*   **Stack**: `Node.js` · `Express` · `React` · `Supabase` · `Docker` · `Stripe`

### 🧠 **ZenProof** — Privacy-Preserving Trust & Identity Protocol
> **Research & Implementation** · [Published Architecture Paper](https://coderlegion.com/20276/beyond-identity-rethinking-trust-infrastructure-through-zero-knowledge-verification)

Zero-knowledge verification system for secure identity management, eliminating third-party trust requirements.
*   **Cryptography**: Created ZK-SNARK verification circuits bound to W3C Decentralized Identifiers (DIDs) and IPFS metadata.
*   **Guarantees**: Allows users to cryptographically verify attributes (e.g., citizenship, skill level) without exposing raw data.
*   **Publication**: Authored and published the formal IEEE-style architecture paper on distributed credential verification.
*   **Stack**: `zk-SNARKs` · `IPFS` · `TypeScript` · `Solidity` · `zkSync`

### 🔀 **ChainSplit** — Non-Custodial Multi-Vault Settlement Engine
> **Smart Contract Architecture** · [Live Application](https://chainsplit.vercel.app)

A decentralized bill-splitting and debt-minimization engine operating on Cronos EVM.
*   **Smart Contracts**: Structured using a factory pattern deploying isolated `GroupVault` contracts to ensure zero pooled-fund custody risks.
*   **Algorithmic Optimization**: Designed a greedy debt-minimization algorithm implemented on-chain to reduce settlement transactions by up to 45%.
*   **Stack**: `Solidity` · `Ethers.js` · `React` · `MongoDB`

### 🤖 **OnTrade** — Compiled On-Chain Automation Engine
> **Distributed Logic**

A visual, visual-programming workflow compiler executing automation instructions natively on-chain.
*   **Execution**: Compiles visual trigger nodes (price feed changes, oracle signals) directly into bytecode representing on-chain logic, removing backend polling dependencies.
*   **Integrations**: Integrates LLM routing nodes (via OpenAI API) for evaluating trading triggers before executing smart contract calls.
*   **Stack**: `TypeScript` · `OpenAI API` · `Solidity` · `Ethers.js`

### 🪪 **Credora** — Enterprise Permissioned Ledger Platform
> **Identity and Access Management** · [Live App](https://credora-veripass.netlify.app)

Double-layered private permissioned portal submitted to the **Blockchain India Challenge (MeitY)**.
*   **Ledger Setup**: Deployed on Hyperledger Fabric with dual MetaMask + X.509 MSP authentication controls.
*   **Stack**: `Hyperledger Fabric` · `Go` · `React`

---

## 📦 Open Source Contributions

| Target Repository | Contribution Details | Status |
| :--- | :--- | :--- |
| **OpenZeppelin Contracts** | [PR #782](https://github.com/OpenZeppelin/contracts-wizard/pull/782) — Clarified legacy Yarn classic package management setups | `Merged` |
| **Scaffold-ETH 2** | Modified `useScaffoldReadContract` hooks to treat `contractAddress` parameters as optional | `Shipped` |
| **Panana Predictions** | Integrated HuggingFace NLP models to power MEV-resistant sentiment outcome resolution on Aptos | `Shipped` |

---

## 🏆 Hackathon Records

```
┌──────────────────────────────────────────────────────────────────┐
│                      OFFICIAL LEAGUE RECORD                      │
├──────────────────────────────────────────────────────────────────┤
│  🏆 Tech Masters '26 (Overall Winner)                           │
│  🏆 RAC-A-THON (Overall Winner)                                  │
│  🥈 Google Developer Hackathon (Runner Up)                       │
│  🚀 Blockchain India Challenge 2024 (MeitY Submission)           │
│  ⭐ 10+ Total Hackathon Finals & Submissions                     │
└──────────────────────────────────────────────────────────────────┘
```

<details>
<summary>🔍 Expand Full Hackathon Timeline</summary>

| Hackathon / Event | Achievement / Role |
| :--- | :--- |
| **Tech Masters '26** | **Winner** |
| **RAC-A-THON** | **Winner** |
| **Google Developer Hackathon** | **Runner Up** |
| **HACKTU 6.0** | **Finalist** |
| **WE Hack** | **Top 6** |
| **Hack N Win 2.0** | **Finalist** |
| **Deep Funding Round** | **Top 5** |
| **Build on Aptos** | **Finalist** |
| **Pivot Hackathon** | **Finalist** |
| **Hack Beyond The Limits** | **Technical Lead & Organizer (200+ Developers)** |

</details>

---

## 🛠️ Technology Stack

```
[Languages]      : TypeScript · Rust · Go · Move · Solidity · Python
[Protocols]      : EVM (Ethereum, Polygon, Arbitrum, Base, Cronos) · Move (Aptos)
[Cryptography]   : ZK-SNARKs (Semaphore) · W3C DIDs · IPFS
[Enterprise]     : Hyperledger Fabric
[Ops & Backend]  : Docker · Node.js · PostgreSQL · MongoDB · Supabase · Vercel
```

---

## 📊 Telemetry Stats

<p align="center">
  <img height="165em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=0xMayurrr&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=ffffff&icon_color=00D9FF&text_color=9ca3af"/>
  <img height="165em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=0xMayurrr&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=ffffff&text_color=9ca3af&langs_count=8"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=0xMayurrr&theme=tokyonight&hide_border=true&background=0d1117&ring=00D9FF&fire=00D9FF&currStreakLabel=ffffff"/>
</p>

---

### `> System Status`

```rust
fn current_status() -> StatusReport {
    StatusReport {
        status: "Actively Shipping",
        open_to: [
            "Web3 Infrastructure Engineering",
            "Smart Contract / Protocol Engineering",
            "Core Developer Tooling Roles"
        ],
        direct_comms: "mayurkarthick2006@gmail.com"
    }
}
```
