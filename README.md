<div align="center">

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   ██████╗ ██╗  ██╗███╗   ███╗ █████╗ ██╗   ██╗██████╗ ██████╗     │
│  ██╔═████╗╚██╗██╔╝████╗ ████║██╔══██╗╚██╗ ██╔╝██╔══██╗██╔══██╗    │
│  ██║██╔██║ ╚███╔╝ ██╔████╔██║███████║ ╚████╔╝ ██████╔╝██████╔╝    │
│  ████╔╝██║ ██╔██╗ ██║╚██╔╝██║██╔══██║  ╚██╔╝  ██╔══██╗██╔══██╗    │
│  ╚██████╔╝██╔╝ ██╗██║ ╚═╝ ██║██║  ██║   ██║   ██║  ██║██║  ██║    │
│   ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝   │
│                                                                     │
│            building on-chain infrastructure, one tx at a time      │
└─────────────────────────────────────────────────────────────────────┘
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=2500&pause=1000&color=a3e635&center=true&vCenter=true&width=700&lines=Web3+Developer+%26+Smart+Contract+Engineer;ZK+%2B+DID+Infrastructure+Builder;SaaS+Founder+%E2%80%94+rpcforge.dev+is+live+%E2%9A%A1;Vibecoder+%7C+engineering_the_future()%3B)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/portfolio-mayurworks.vercel.app-a3e635?style=flat-square&logo=vercel&logoColor=black)](https://mayurworks.vercel.app/)&nbsp;
[![LinkedIn](https://img.shields.io/badge/linkedin-mayurp03-a3e635?style=flat-square&logo=linkedin&logoColor=black)](https://www.linkedin.com/in/mayurp03/)&nbsp;
[![X](https://img.shields.io/badge/x-@0xMayurrr-a3e635?style=flat-square&logo=x&logoColor=black)](https://x.com/0xMayurrr)&nbsp;
[![Research](https://img.shields.io/badge/research-hashnode-a3e635?style=flat-square&logo=hashnode&logoColor=black)](https://zenproof-research.hashnode.dev/)&nbsp;
[![Email](https://img.shields.io/badge/email-mayurkarthick2006-a3e635?style=flat-square&logo=gmail&logoColor=black)](mailto:mayurkarthick2006@gmail.com)&nbsp;
[![Views](https://komarev.com/ghpvc/?username=0xMayurrr&color=a3e635&style=flat-square&label=profile+views)](https://github.com/0xMayurrr)

</div>

<br/>

---

```bash
$ cat identity.sol
```

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.26;

contract MayurP {
    string public name    = "Mayur P.";
    string public handle  = "@0xMayurrr";
    string public degree  = "BSc Computer Technology — Blockchain & Distributed Computing";
    string public college = "Rathinam University, Tamil Nadu · Class of 2026";
    string public status  = "Shipping SaaS · Hunting remote Web3 roles · Open to relocation 🌍";

    string[] public shipping = [
        "RPCForge   ⚡  — Multi-chain RPC Gateway SaaS     [ LIVE on Product Hunt ]",
        "ZenProof   🔐  — Privacy-Preserving Trust Infra   [ Research live on Hashnode ]",
        "ProofHire  🧠  — AI Proof-of-Skill Hiring Network [ Roadmap ]"
    ];

    string[] public published = [
        "zenproof-research.hashnode.dev — ZK + DID architecture deep dives",
        "IEEE-style paper — ZenProof V1: ZK-SNARK + W3C DID credential system"
    ];

    string[] public openTo = [
        "Smart Contract Dev", "Protocol Engineering",
        "Web3 Infra", "Full-Stack dApp", "DevRel"
    ];

    string[] public vibeStack = ["Claude Code", "Cursor", "GitHub Copilot"];

    function edge() external pure returns (string memory) {
        return "10+ hackathon wins. Merged OSS PRs. Deployed contracts. Live SaaS. Research published.";
    }
}
```

---

```bash
$ ls -la ~/projects/web3/
```

```
drwxr-xr-x  RPCForge/           ⚡  Multi-chain RPC Gateway SaaS            [LIVE · Product Hunt]
drwxr-xr-x  ZenProof/           🔐  Privacy-Preserving Trust Infrastructure  [Research Published]
drwxr-xr-x  OnTrade/            🟠  n8n-style On-Chain Automation
drwxr-xr-x  ChainSplit/         🟡  Decentralized Bill Splitting · Cronos EVM
drwxr-xr-x  Credora/            🟢  Enterprise Credentials · Hyperledger Fabric
drwxr-xr-x  AptosMarket/        🔮  Prediction Market · FinBERT Sentiment Oracle
drwxr-xr-x  AI-ContractAuditor/ 🛡️  Smart Contract Security Tool · NodeOps x CreateOS
drwxr-xr-x  CryptoWallet/       📱  Institutional-Grade Mobile Ethereum Wallet

$ ls -la ~/projects/web2/

drwxr-xr-x  CampusAidBuddy/     🎓  Gemini RAG Campus Assistant · Tech Masters '26 Winner 🏆
drwxr-xr-x  VibeStay/           🏠  Vibe-Driven AI Stay Booking Platform
```

---

```bash
$ cat ~/projects/web3/RPCForge/README.md
```

> Tired of Alchemy's surprise bills and Infura's rate limits. So I built my own — and shipped it as a product.

```
  your dApp · hardhat · ethers.js
          │   x-api-key: rpcf_xxx
          ▼
 ╔══════════════════════════════════════════════╗
 ║           ⚡  RPCForge  Gateway              ║
 ║                                              ║
 ║  🔑 API Key Auth     🚦 Per-Tier Rate Limit  ║
 ║  ⚡ Response Cache   🔄 Multi-node Failover  ║
 ║  🚫 Method Guard     📊 WebSocket Dashboard  ║
 ║  🛝 RPC Playground   🗺️  Chain Heatmaps      ║
 ║  📈 Latency Tracker  🔑 Key-level Analytics  ║
 ╚══════════════════════╦═══════════════════════╝
                        │
      ┌─────────────────┼──────────────┬──────────────┐
      ▼                 ▼              ▼              ▼
   Ethereum          Polygon          BSC          Arbitrum
   + Sepolia         Mainnet         Mainnet         One
```

```
# vs the competition

feature             public-rpcs    alchemy/infura    rpcforge
────────────────────────────────────────────────────────────
api key auth             ✗              ✓               ✓
multi-node failover      ✗              ✓               ✓
per-key rate limits      ✗              ✓               ✓
self-hostable            ✓              ✗               ✓
open source              ✓              ✗               ✓
real-time dashboard      ✗              ✓               ✓
vendor lock-in           ✗              🔒              ✗
pricing               free            $$$         free·$9·$29·$99
```

```bash
stack   →  Node.js · Express · React 18 · Supabase · Docker · Railway · Vercel · Stripe
chains  →  Ethereum · Polygon · BSC · Arbitrum · Sepolia
live    →  rpcforge.dev
launch  →  Product Hunt [ LAUNCHED ]
```

[![live](https://img.shields.io/badge/🔴_live-rpcforge.dev-a3e635?style=flat-square&logo=vercel&logoColor=black)](https://rpcforge.dev)&nbsp;
[![product hunt](https://img.shields.io/badge/product_hunt-launched-DA552F?style=flat-square&logo=producthunt&logoColor=white)](https://www.producthunt.com/@0xmayurrr)&nbsp;
[![dashboard](https://img.shields.io/badge/dashboard-open-6467f2?style=flat-square)](https://rpcforge.dev/dashboard)&nbsp;
[![repo](https://img.shields.io/badge/repo-RPCForge-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/RPCForge)

---

```bash
$ cat ~/projects/web3/ZenProof/README.md
```

> Your credentials. Your proofs. Zero surveillance. Built the decentralized version before the big players did.

```
  you
   │  claim: "I built X" / "I have this degree" / "I contributed here"
   ▼
  ┌────────────────────────────────────────────────────────┐
  │                  ZenProof Trust Layer                  │
  │                                                        │
  │   ZK-SNARK proof gen  →  Semaphore circuit             │
  │   W3C DID identity    →  portable · chain-agnostic     │
  │   IPFS credential     →  censorship-resistant          │
  │   ProofHire (soon)    →  AI proof-of-skill hiring      │
  └────────────────────────────────────────────────────────┘
   │
   ▼
  verifier receives:  ✅ or ❌   (nothing else leaks)
```

```bash
stack      →  ZK-SNARKs · Semaphore · W3C DIDs · IPFS · TypeScript · Ethereum
research   →  zenproof-research.hashnode.dev
roadmap    →  ProofHire — AI proof-of-skill hiring network
paper      →  IEEE-style ZK credential architecture · ZenProof V1
```

[![research](https://img.shields.io/badge/research-zenproof--research.hashnode.dev-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://zenproof-research.hashnode.dev/)&nbsp;
[![repo](https://img.shields.io/badge/repo-ZenProof-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/ZenProof-)

---

```bash
$ cat ~/projects/web3/ChainSplit/README.md
```

> Split bills. Settle debts. On-chain. No middlemen. No trust issues. Just code.

```bash
pattern  →  Factory + GroupVault — each group gets its own contract, no shared custody
algo     →  greedy debt-minimization for optimal on-chain settlements
guards   →  custom nonReentrant · onlyAdmin/onlyMember access control
ipfs     →  metadata via Pinata · RainbowKit + WalletConnect v2
address  →  0xe9256300bb409b5Cf8CF16aDD6A0aDB0cc72E5bf  (Cronos Testnet · Chain 338)
stack    →  Solidity 0.8.24 · React 18 · Wagmi v2 · MongoDB
```

[![live](https://img.shields.io/badge/live-chainsplit.vercel.app-a3e635?style=flat-square&logo=vercel&logoColor=black)](https://chainsplit.vercel.app)&nbsp;
[![repo](https://img.shields.io/badge/repo-ChainSplit-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/ChainSplit)

---

```bash
$ cat ~/projects/web3/OnTrade/README.md
```

> n8n for on-chain logic. Build crypto strategies with visual blocks — no backend, no middlemen. Strategy → compile → chain.

```bash
nodes   →  price triggers · indicators · AI reasoning · sentiment checks
model   →  no centralized servers, pure on-chain execution
stack   →  TypeScript · n8n-inspired visual builder
```

[![repo](https://img.shields.io/badge/repo-Ontrade--Chain-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/Ontrade-Chain)

---

```bash
$ cat ~/projects/web3/Credora/README.md
```

> Real-world credentials — degrees, certs, DAO badges — turned into Verifiable Credentials. Prove things without revealing everything.

```bash
auth    →  MetaMask + X.509 MSP dual layer
fraud   →  AI-powered detection on credential submissions
submit  →  Blockchain India Challenge 2024 (MeitY) 🇮🇳
stack   →  Hyperledger Fabric 2.5 · Golang chaincode · ZK privacy layer
```

[![live](https://img.shields.io/badge/live-credora--veripass.netlify.app-a3e635?style=flat-square&logo=netlify&logoColor=black)](https://credora-veripass.netlify.app)&nbsp;
[![repo](https://img.shields.io/badge/repo-Credora_Digital-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/Credora_Digital)

---

```bash
$ cat ~/projects/web3/AptosMarket/README.md
```

> Commit-reveal prediction market on Aptos with HuggingFace FinBERT NLP oracle feeding real market signals.

```bash
oracle  →  HuggingFace FinBERT — real NLP sentiment as a market signal feed
pattern →  commit-reveal scheme — MEV-resistant, fair outcome resolution
stack   →  Move smart contracts · Next.js · Petra wallet integration
```

[![repo](https://img.shields.io/badge/repo-panana--predictions-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/panana-predictions)

---

```bash
$ cat ~/projects/web3/AI-ContractAuditor/README.md
```

> Production-ready AI-native smart contract security auditor. Detects Solidity vulnerabilities, scores security, auto-generates fixed code — under 2 seconds, no API keys required. Built for NodeOps × CreateOS contest.

```bash
input   →  any Solidity contract
output  →  vulnerability report · severity score · patched contract
speed   →  < 2 seconds
stack   →  TypeScript · CreateOS Skills · AI
```

[![repo](https://img.shields.io/badge/repo-AI--ContractAuditor-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/AI-ContractAuditor)

---

```bash
$ cat ~/projects/web3/CryptoWallet/README.md
```

> Institutional-grade non-custodial mobile Ethereum wallet. AES-256 seed phrase encryption, live portfolio charts, native Send/Receive/Swap — ships as Android APK.

```bash
security  →  AES-256 seed phrase encryption
features  →  live portfolio charts · Send · Receive · Swap
stack     →  React Native · Ethers.js v5
output    →  Android APK
```

[![repo](https://img.shields.io/badge/repo-CryptoWallet-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/CryptoWallet)

---

```bash
$ cat ~/projects/web2/CampusAidBuddy/README.md
```

> 4-role campus system (Student · Faculty · Admin · Visitor) with Gemini-powered RAG assistant. Built for Tech Masters '26 — won. 🏆

```bash
roles   →  Student · Faculty · Admin · Visitor
ai      →  Gemini-powered RAG assistant
stack   →  React · Firebase · Gemini AI
result  →  Tech Masters '26 — Winner 🏆
```

[![repo](https://img.shields.io/badge/repo-Campus_Aid_buddy-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/Campus_Aid_buddy)

---

```bash
$ cat ~/projects/web2/VibeStay/README.md
```

> Filter stays by mood and aesthetic — not just location. AI speech recognition + vibe-based recommendations.

```bash
filter  →  by mood, aesthetic, vibe — not just location
ai      →  speech recognition · vibe-based recommendations
stack   →  JavaScript · AI
```

[![live](https://img.shields.io/badge/live-vibestayy.netlify.app-a3e635?style=flat-square&logo=netlify&logoColor=black)](https://vibestayy.netlify.app/)&nbsp;
[![repo](https://img.shields.io/badge/repo-Vibe_Stay-181717?style=flat-square&logo=github)](https://github.com/0xMayurrr/Vibe_Stay)

---

```bash
$ git log --oneline --author="0xMayurrr" --all --oss-only
```

```
✅ merged   OpenZeppelin/contracts-wizard    PR #782 — fixed yarn classic v1.x install docs
✅ shipped  scaffold-eth-2                   contractAddress optional in useScaffoldReadContract
✅ shipped  panana-predictions (Aptos)       HuggingFace FinBERT NLP sentiment oracle integration
```

---

```bash
$ cat ~/research/publications.md
```

```
📓  ZenProof Research Blog
    url    →  zenproof-research.hashnode.dev
    topics →  ZK-SNARKs · W3C DIDs · Privacy-Preserving Trust Infrastructure

📄  IEEE-style Paper
    title  →  ZenProof V1: Decentralized ZK Credential System Architecture
    stack  →  ZK-SNARK + W3C DID + IPFS
```

[![read on hashnode](https://img.shields.io/badge/read-zenproof--research.hashnode.dev-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://zenproof-research.hashnode.dev/)

---

```bash
$ cat ~/wins.log
```

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
📌  Future Interns                Blockchain & Crypto Internship
```

---

```bash
$ cat ~/.stack
```

```
[blockchain & contracts]
Solidity · Move · Hardhat · Ethers.js · Wagmi · OpenZeppelin · Hyperledger Fabric

[zk & decentralized identity]
ZK-SNARKs · Semaphore · W3C DIDs · IPFS

[multi-chain]
Ethereum · Polygon · Arbitrum · BNB Chain · Base · Cronos EVM · Aptos

[languages & fullstack]
TypeScript · JavaScript · Python · Go · React · Next.js · Node.js

[infra & tools]
Docker · PostgreSQL · MongoDB · Supabase · Railway · Vercel · Stripe

[vibe stack]
Claude Code · Cursor · GitHub Copilot
```

---

```bash
$ gh stats --user 0xMayurrr
```

<p align="center">
<img height="175em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=0xMayurrr&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=a3e635&icon_color=a3e635&text_color=c9d1d9" />
<img height="175em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=0xMayurrr&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a3e635&text_color=c9d1d9&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=0xMayurrr&theme=tokyonight&hide_border=true&background=0d1117&ring=a3e635&fire=a3e635&currStreakLabel=a3e635" />
</p>

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=0xMayurrr&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=0xMayurrr&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=a3e635&line=4d7c0f&point=a3e635" />
</p>

---

```bash
$ snake --dark-mode --user 0xMayurrr
```

<div align="center">

![snake](https://github.com/0xMayurrr/0xMayurrr/blob/output/github-snake-dark.svg)

</div>

---

```bash
$ echo "looking for remote Web3 roles — smart contract dev, protocol engineering,"
$ echo "infra, devrel. open to relocation. if you're building on-chain and need"
$ echo "someone who moves fast and thinks in primitives — let's talk."
$ open --links
```

```
portfolio  →  mayurworks.vercel.app
linkedin   →  linkedin.com/in/mayurp03
x          →  x.com/0xMayurrr
research   →  zenproof-research.hashnode.dev
email      →  mayurkarthick2006@gmail.com
superteam  →  earn.superteam.fun
```

<div align="center">

[![portfolio](https://img.shields.io/badge/portfolio-000?style=for-the-badge&logo=vercel&logoColor=a3e635)](https://mayurworks.vercel.app/)&nbsp;
[![linkedin](https://img.shields.io/badge/linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayurp03/)&nbsp;
[![x](https://img.shields.io/badge/x-000?style=for-the-badge&logo=x&logoColor=a3e635)](https://x.com/0xMayurrr)&nbsp;
[![research](https://img.shields.io/badge/research-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)](https://zenproof-research.hashnode.dev/)&nbsp;
[![email](https://img.shields.io/badge/email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mayurkarthick2006@gmail.com)&nbsp;
[![superteam](https://img.shields.io/badge/superteam-9945FF?style=for-the-badge&logo=solana&logoColor=white)](https://earn.superteam.fun)

</div>

<br/>

<div align="center">

```
# the chain doesn't lie.
# neither does the commit history.
```

</div>
