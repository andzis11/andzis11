<div align="center">

# Andzisone
### **Security Researcher · Systems & Protocol Security · Algorithmic Engineering**

<p>
  <a href="https://x.com/RianputraSk8"><img src="https://img.shields.io/badge/X-@RianputraSk8-black?style=flat-square&logo=x&logoColor=white" alt="X / Twitter" /></a>
  <a href="https://www.flowmusic.app/andzisone"><img src="https://img.shields.io/badge/Flow%20Music-andzisone-E62117?style=flat-square&logo=youtubemusic&logoColor=white" alt="Flow Music" /></a>
  <a href="#-security-research"><img src="https://img.shields.io/badge/Research-GHSA%20Verified-238636?style=flat-square&logo=github&logoColor=white" alt="GHSA" /></a>
  <a href="#-responsible-disclosure--contact"><img src="https://img.shields.io/badge/Policy-Coordinated%20Disclosure-0969da?style=flat-square&logo=securityscorecard&logoColor=white" alt="CVD Policy" /></a>
</p>

<p align="center">
  Focusing on <b>vulnerability research</b> (memory safety, confidential enclaves, cryptographic protocol bindings, supply chain parsing), <br/>
  <b>low-latency systems</b>, and <b>Web3 algorithmic infrastructure</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/AWS%20Nitro%20Enclaves-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

---

</div>

## 🛡️ Security Research

Verified disclosures with official vendor credit and GitHub Security Advisories (GHSA):

| Target | Advisory / Evidence | Finding Summary | Impact & Status |
|:---|:---|:---|:---|
| **[`xevrion/hatchzip`](https://github.com/xevrion/hatchzip)** | [`GHSA-cq63-4gv9-w2gc`](https://github.com/xevrion/hatchzip/security/advisories/GHSA-cq63-4gv9-w2gc) | Symlinked `.hatchzip-part` name redirects extraction to write outside output directory | `Fixed 0.1.6` · `CWE-59` · Shared credit |
| **[`xevrion/hatchzip`](https://github.com/xevrion/hatchzip)** | [`GHSA-m6m5-qcjx-55gv`](https://github.com/xevrion/hatchzip/security/advisories/GHSA-m6m5-qcjx-55gv) | Progress files shipped with archive let resume/restore replace arbitrary files | `Fixed 0.1.6` · `CWE-345` · Sole reporter |
| **[`shieldfive/crypto`](https://github.com/shieldfive/crypto)** | [`CHANGELOG`](https://github.com/shieldfive/crypto/blob/main/CHANGELOG.md) · [`PR #55`](https://github.com/shieldfive/crypto/pull/55) | Upload-proof scope: proof-binding claim exceeded MAC's actual coverage | `Credited` (2026-09-23) · Protocol audit |
| **[`PayPerQ/ppq-enclave-proxy`](https://github.com/PayPerQ/ppq-enclave-proxy)** | [`GHSA-33j5-hgc8-9mgg`](https://github.com/PayPerQ/ppq-enclave-proxy/pull/360) · [`PR #360`](https://github.com/PayPerQ/ppq-enclave-proxy/pull/360) | Body-parse error echoed unsealed EHBP plaintext + unbounded line pump worker OOM DoS | `Fixed` · Nitro Enclave · Credited reporter |

---

## 🔬 Core Focus & Research Domains

```
[ Vulnerability Research ] ──> Memory & State Safety ──> Cryptographic Bindings ──> Confidential Enclaves
[ Systems & Web3 Infra  ] ──> Low-Latency Engines   ──> MEV Arbitrage          ──> Asynchronous TUI Wallets
```

- **Vulnerability Research**: Coordinated Vulnerability Disclosure (CVD), path traversal & archive sanitization, enclave proxy boundaries, cryptographic proof-binding validation.
- **Low-Latency & Web3 Systems**: Dynamic bin liquidity management (Solana Meteora DLMM), cross-pool MEV arbitrage discovery, asynchronous TUI architectures.
- **Autonomous Agents**: Quantitative AI agents for market microstructure and order flow analysis.

---

## 🚀 Featured Engineering & Tooling

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/andzis11/MeteoraDLLM">MeteoraDLLM</a></h3>
      <p>Automated liquidity management & active dynamic bin rebalancing architecture tailored for <b>Solana Meteora DLMM</b> liquidity pools.</p>
      <code>Python</code> <code>Solana</code> <code>DeFi</code>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/andzis11/andzis-arbitrage-mode">andzis-arbitrage-mode</a></h3>
      <p>High-efficiency <b>MEV cross-pool arbitrage engine</b> designed for rapid cycle discovery and execution across on-chain liquidity routes.</p>
      <code>TypeScript</code> <code>MEV</code> <code>Web3</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💻 <a href="https://github.com/andzis11/octra_pre_client">octra_pre_client</a></h3>
      <p>Retro DOS-era TUI client for <b>Octra Network</b> powered by a modern non-blocking asynchronous architecture and terminal UX.</p>
      <code>Python</code> <code>AsyncIO</code> <code>TUI</code>
    </td>
    <td width="50%" valign="top">
      <h3>📊 <a href="https://github.com/andzis11/Ex-XAU">Ex-XAU</a></h3>
      <p>Autonomous AI market agent analyzing macroeconomic trends, multi-timeframe price action, and order flow metrics for gold (XAU).</p>
      <code>Python</code> <code>AI-Agent</code> <code>Finance</code>
    </td>
  </tr>
</table>

---

## 🤝 Responsible Disclosure & Contact
- **Ethics**: All vulnerability research is conducted strictly under **Coordinated Vulnerability Disclosure (CVD)** guidelines.
- **Direct Message**: [X / @RianputraSk8](https://x.com/RianputraSk8)
- **Music & Playlists**: [Flow Music / andzisone](https://www.flowmusic.app/andzisone)
- **Security Inquiries**: Available for coordinated vulnerability disclosure and technical verification via repository security advisories.
<!---
andzis11/andzis11 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
