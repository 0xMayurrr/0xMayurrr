<div align="center">

```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║    ██████╗ ██╗  ██╗███╗   ███╗ █████╗ ██╗   ██╗██████╗           ║
║   ██╔═████╗╚██╗██╔╝████╗ ████║██╔══██╗╚██╗ ██╔╝██╔══██╗          ║
║   ██║██╔██║ ╚███╔╝ ██╔████╔██║███████║ ╚████╔╝ ██████╔╝          ║
║   ████╔╝██║ ██╔██╗ ██║╚██╔╝██║██╔══██║  ╚██╔╝  ██╔══██╗          ║
║   ╚██████╔╝██╔╝ ██╗██║ ╚═╝ ██║██║  ██║   ██║   ██║  ██║          ║
║    ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝          ║
║                                                                   ║
║         building on-chain infrastructure, one tx at a time       ║
╚═══════════════════════════════════════════════════════════════════╝
```

</div>

```bash
$ whoami
> mayur-p  # BSc Computer Technology · Blockchain & Distributed Computing
            # Rathinam University, Tamil Nadu · 2026

$ cat identity.json
{
  "handle"    : "0xMayurrr",
  "type"      : "Web3 Developer + Vibecoder",
  "status"    : "shipping SaaS · hunting remote Web3 roles · open to relocation 🌍",
  "building"  : ["RPCForge ⚡", "ZenProof 🔐", "ProofHire 🧠"],
  "published" : "zenproof-research.hashnode.dev",
  "vibe_stack": ["Claude Code", "Cursor", "GitHub Copilot"],
  "edge"      : "10+ hackathon wins · merged OSS PRs · deployed contracts · live SaaS"
}
```

---

## `~/projects` — things I actually shipped

---

### ⚡ RPCForge — *Live on Product Hunt*
> Multi-chain RPC Gateway SaaS. Open-source alternative to Alchemy & Infura.

```
  ethers.js / hardhat / wagmi
        │  x-api-key: rpcf_xxx
        ▼
  ┌─────────────────────────────────────────┐
  │            RPCForge Gateway             │
  │                                         │
  │  auth → rate-limit → cache → failover   │
  │  method guard · analytics · playground  │
  └──────────────┬──────────────────────────┘
                 │
     ┌───────────┼───────────┬──────────┐
     ▼           ▼           ▼          ▼
  Ethereum    Polygon      BSC      Arbitrum
```

```
stack  →  Node.js · Express · React 18 · Supabase · Docker · Railway · Stripe
pricing→  Free · $9 · $29 · $99
live   →  rpcforge.dev
```

[![rpcforge.dev](https://img.shields.io/badge/live-rpcforge.dev-6467f2?style=flat-square)](https://rpcforge.dev)
[![Product Hunt](https://img.shields.io/badge/product_hunt-launched-DA552F?style=flat-square&logo=producthunt&logoColor=white)](https://www.producthunt.com/@0xmayurrr)
[![repo](https://img.shields.io/badge/repo-RPCForge-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/RPCForge)

---

### 🔐 ZenProof — *Privacy-Preserving Trust Infrastructure*
> Your credentials, your proofs — without leaking your identity.

```
  you
   │  prove you shipped, without exposing everything
   ▼
  ┌──────────────────────────────────────────────┐
  │              ZenProof Trust Layer            │
  │                                              │
  │  ZK-SNARK proof gen  ·  W3C DID identity     │
  │  IPFS credential store  ·  Semaphore circuit │
  └──────────────────────────────────────────────┘
   │
   ▼
  verifier gets:  ✅  (nothing else)
```

```
stack      →  ZK-SNARKs · Semaphore · W3C DIDs · IPFS · TypeScript · Ethereum
research   →  zenproof-research.hashnode.dev
roadmap    →  ProofHire — AI proof-of-skill hiring network
```

[![research blog](https://img.shields.io/badge/research-hashnode-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://zenproof-research.hashnode.dev/)
[![repo](https://img.shields.io/badge/repo-ZenProof-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/ZenProof-)

---

### 🔗 ChainSplit — *Trustless Bill Splitting on Cronos EVM*

```
  group created  →  GroupVault deployed  →  greedy debt minimization  →  settle on-chain
```

```
pattern →  Factory + GroupVault (non-custodial, no shared wallets)
guard   →  custom nonReentrant · onlyAdmin/onlyMember
extras  →  IPFS metadata via Pinata · RainbowKit + WalletConnect v2
address →  0xe9256300bb409b5Cf8CF16aDD6A0aDB0cc72E5bf  (Cronos Testnet 338)
stack   →  Solidity 0.8.24 · React 18 · Wagmi v2 · MongoDB
```

[![live](https://img.shields.io/badge/live-chainsplit.vercel.app-646cf2?style=flat-square)](https://chainsplit.vercel.app)
[![repo](https://img.shields.io/badge/repo-ChainSplit-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/ChainSplit)

---

### 🟠 OnTrade — *n8n for On-Chain Logic*

```
  strategy → visual blocks → compile → execute on-chain (no backend, ever)
```

```
nodes   →  price triggers · indicators · AI reasoning · sentiment feeds
model   →  no centralized servers, pure on-chain execution
stack   →  TypeScript · n8n-style builder
```

[![repo](https://img.shields.io/badge/repo-Ontrade--Chain-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/Ontrade-Chain)

---

### 🟢 Credora — *Enterprise Verifiable Credentials on Hyperledger Fabric*

```
  institution issues cred  →  ZK privacy layer  →  user proves it  →  verifier confirms
```

```
auth    →  MetaMask + X.509 MSP dual layer
fraud   →  AI-powered detection on submissions
stack   →  Hyperledger Fabric 2.5 · Golang chaincode
submit  →  Blockchain India Challenge 2024 (MeitY)
```

[![live](https://img.shields.io/badge/live-credora--veripass.netlify.app-00C7B7?style=flat-square)](https://credora-veripass.netlify.app)
[![repo](https://img.shields.io/badge/repo-Credora_Digital-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/Credora_Digital)

---

### 🔮 Aptos Prediction Market + FinBERT Sentiment Oracle

```
  HuggingFace FinBERT → NLP sentiment signal → commit-reveal market → Move contracts → Petra wallet
```

[![repo](https://img.shields.io/badge/repo-0xMayurrr-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr)

---

### 🛡️ AI Smart Contract Auditor — *Production Security Tool (NodeOps x CreateOS)*

```
  solidity input  →  vulnerability scan  →  severity score  →  auto-patched contract
                                                                  (under 2 seconds)
```

[![repo](https://img.shields.io/badge/repo-AI--ContractAuditor-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/AI-ContractAuditor)

---

## `~/oss` — open source I actually touched

```
repo                              contribution                              status
──────────────────────────────────────────────────────────────────────────────────
OpenZeppelin/contracts-wizard     PR #782 — fixed yarn classic v1.x docs   ✅ merged
scaffold-eth-2                    contractAddress optional in useScaffold   ✅ shipped
panana-predictions (Aptos)        FinBERT NLP sentiment oracle integration  ✅ shipped
```

---

## `~/research` — writing & thinking out loud

```
blog   →  zenproof-research.hashnode.dev
          ZK-SNARKs · W3C DIDs · Privacy-Preserving Trust Infrastructure

paper  →  IEEE-style architecture paper on decentralized ZK credential systems
          (ZenProof V1 — ZK-SNARK + W3C DID + IPFS stack)
```

[![hashnode](https://img.shields.io/badge/zenproof--research.hashnode.dev-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://zenproof-research.hashnode.dev/)

---

## `~/wins` — proof of work

```
🏆  Tech Masters '26              Winner
🏆  RAC-A-THON                    Winner
🥈  Google Developer Hackathon    Runner Up
🎯  HACKTU 6.0                    Finalist
🎯  WE Hack                       Top 6
🎯  Hack N Win 2.0                Finalist
🎯  Deep Funding Round            Top 5
🎯  Build on Aptos                Finalist
🎯  Pivot Hackathon               Finalist
🛠️  Hack Beyond The Limits        Technical Organizer · 24h national hackathon
🧑‍🏫  Smart India Hackathon         Team Mentor
```

---

## `~/stack`

```
contracts   →  Solidity · Move · Hardhat · Foundry · OpenZeppelin · Hyperledger Fabric
zk + did    →  ZK-SNARKs · Semaphore · W3C DIDs · IPFS
chains      →  Ethereum · Polygon · Arbitrum · BNB Chain · Base · Cronos · Aptos
frontend    →  React · Next.js · Wagmi · RainbowKit · ethers.js · TypeScript
backend     →  Node.js · Express · Golang · Python
infra       →  Docker · Supabase · PostgreSQL · MongoDB · Railway · Vercel · Stripe
vibe        →  Claude Code · Cursor · GitHub Copilot
```

---

## `~/stats`

<p align="center">
<img height="175em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=0xMayurrr&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=a3e635&icon_color=a3e635&text_color=c9d1d9" />
<img height="175em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=0xMayurrr&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a3e635&text_color=c9d1d9&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=0xMayurrr&theme=tokyonight&hide_border=true&background=0d1117&ring=a3e635&fire=a3e635&currStreakLabel=a3e635" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=0xMayurrr&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=a3e635&line=4d7c0f&point=a3e635" />
</p>

---

## `~/connect`

```bash
$ open https://mayurworks.vercel.app/        # portfolio
$ open https://linkedin.com/in/mayurp03/     # linkedin
$ open https://x.com/0xMayurrr              # x / twitter
$ open https://zenproof-research.hashnode.dev # research
$ mailto mayurkarthick2006@gmail.com         # email
```

> looking for **remote Web3 roles** — smart contract dev, protocol engineering, infra, devrel.  
> open to relocation. if you're building on-chain and need someone who thinks in primitives, dm me.

---

<div align="center">

```
the chain doesn't lie.
neither does the commit history.
```

*— 0xMayurrr*

</div>
