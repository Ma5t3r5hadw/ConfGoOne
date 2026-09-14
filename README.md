<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d121e,50:2f8ef4,100:8b7bff&height=220&section=header&text=ConfGoOne&fontSize=64&fontColor=f6f9fd&animation=fadeIn&fontAlignY=38&desc=Security%20configuration%20auditing%20that%20reviews%20itself%20the%20moment%20you%20open%20a%20file&descAlignY=58&descSize=18" width="100%" alt="ConfGoOne">

<img src="assets/logo.png" width="88" alt="">

[![Latest Release](https://img.shields.io/github/v/release/Ma5t3r5hadw/ConfGoOne?label=latest&color=2f8ef4&style=for-the-badge)](https://github.com/Ma5t3r5hadw/ConfGoOne/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Ma5t3r5hadw/ConfGoOne/total?color=6fc3ff&style=for-the-badge)](https://github.com/Ma5t3r5hadw/ConfGoOne/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-2f8ef4?style=for-the-badge)](#-download)
[![License](https://img.shields.io/badge/license-Commercial-8b7bff?style=for-the-badge)](#-licensing--pricing)

<a href="https://confgoone.com/"><b>Website</b></a> ·
<a href="#-download"><b>Download</b></a> ·
<a href="#-licensing--pricing"><b>Pricing</b></a> ·
<a href="#-support">Support</a>

</div>

<br>

Give ConfGoOne a configuration — from a file, a live device, or a pasted script's output — and it reviews it **immediately**: what's wrong, why it matters, and exactly how to fix it. No "start scan" button, no setup step. It checks itself against every compliance standard you care about, traces how small issues chain into a real breach, and hands you a report worth sending — in whatever format the person on the other end actually wants.

> This repository holds **releases and the project website only** — how you get the app and see what's new. The application itself is closed source.

<br>

## 📋 Contents

- [What it does](#-what-it-does)
- [Everything included](#-everything-included)
- [How it works](#-how-it-works)
- [Download](#-download)
- [Licensing & pricing](#-licensing--pricing)
- [Privacy & security](#-privacy--security)
- [Support](#-support)

<br>

## ⚡ What it does

| | |
|---|---|
| 🛡 **Dashboard** | Your overall security score and the biggest problems, at a glance, the moment a review finishes. |
| 🔍 **Findings** | Every issue, plainly explained, with exactly how to fix it — not just a severity label. |
| ✅ **Frameworks** | Measured against the standards that matter to you, mapped automatically — or bring your own. |
| ⚡ **Attack Path** | How small issues chain into a real breach, ranked by how dangerous each route actually is. |
| 📊 **Report** | A polished document in one click, in whatever format the reader actually wants. |
| 💬 **AI Assistant** | Ask questions about your own configuration in plain English — every answer is checked before you see it. |
| 📸 **Live Screen Capture** | No config export, no CLI access — point it at a live screen and it reads and reviews what's on it. |

<br>

## 🧩 Everything included

One license unlocks all of it — no add-on packs, no feature paywall inside the app.

<details>
<summary><b>🧠 Review engine</b></summary>
<br>

- Deterministic rule-matching engine — real analysis, not an LLM guess
- Built-in coverage for firewalls, routers, switches, servers, cloud platforms, containers, and databases
- Figures out what it's looking at on its own — no dropdown to fill in first
- Picks up device types it hasn't seen before, automatically
- Scans for exposed secrets and hardcoded credentials
- Tracks known CVEs against the versions it finds — online or fully offline

</details>

<details>
<summary><b>✅ Compliance</b></summary>
<br>

- Every major framework mapped automatically — CIS, NIST 800-53 / 800-171 / CSF, PCI-DSS, ISO 27001, HIPAA, SOC 2, MITRE ATT&CK, DISA STIG, CMMC, FedRAMP, Essential Eight, Cyber Essentials, GDPR, NIS2, IEC 62443, and more
- **Control Harmonization** — one finding mapped to every framework it satisfies at once, instead of proving the same control over and over
- Bring your own framework — describe your own controls and findings map straight to them
- Import a DISA STIG or SCAP benchmark (XCCDF) directly and run it alongside the built-in packs
- CIS benchmark scoring built in
- Configuration drift detection against a saved baseline, with auto-generated remediation PRs

</details>

<details>
<summary><b>⚡ Attack & risk</b></summary>
<br>

- **Attack Path ranking** — traces how small issues chain into a real breach, ranked by how dangerous each route is
- Multi-hop reachability analysis across your whole network, not just one device at a time
- **Cyber Risk Quantification** — turns findings into a dollar-estimated risk exposure using FAIR-style modeling, not just a severity label

</details>

<details>
<summary><b>🤖 AI, entirely optional</b></summary>
<br>

- Off by default — every core feature works without it
- Bring your own provider: local (Ollama), OpenAI, Anthropic, Gemini, OpenRouter, NVIDIA NIM, or any self-hosted OpenAI-compatible endpoint
- An independent AI pass double-checks results before you ever see them
- Ask questions about your own configuration in plain English
- Point it at a live screen and it reads what's there

</details>

<details>
<summary><b>📊 Reporting</b></summary>
<br>

- One-click export to HTML, PDF, Word, or Excel
- A shareable report built for whoever's actually going to read it — an engineer or an executive
- CI/CD REST API to run reviews as part of your own pipeline

</details>

<details>
<summary><b>🗂 Management</b></summary>
<br>

- Suppress and track accepted-risk findings without ever losing them
- Full scan history, kept and searchable
- Group devices into named engagements for client-based, batch auditing
- Scan a whole fleet of devices from one list, not one at a time
- Schedule recurring scans so nothing goes stale
- License activation bound to your machine, not floating around

</details>

<details>
<summary><b>🏢 Multi-tenant / MSP</b></summary>
<br>

- Manage multiple clients or environments from one Enterprise account
- Per-tenant scan quotas and usage tracking
- Cross-device attack chain analysis across an entire managed environment

</details>

<details>
<summary><b>🖥 Platform</b></summary>
<br>

- Open a file, paste output, connect live, or capture a live screen — however you can reach it
- Runs entirely offline by default; nothing leaves your machine unless you turn AI on
- Light and dark themes
- Portable — no install, no admin rights, just run it. Windows and macOS, with Linux underway

</details>

<br>

## 🔄 How it works

```
 1. Input        Open a file, connect live, or share a screen
        │
 2. Recognize    Figures out the device type on its own
        │
 3. Review       Full deterministic pass + optional AI validation
        │
 4. Results      Score, findings, and the riskiest attack path
        │
 5. Export       One click, whatever format you need
```

There's no "start scan" button to remember — the review begins the instant you give it something to look at.

<br>

## 📥 Download

Grab the latest version from **[Releases](https://github.com/Ma5t3r5hadw/ConfGoOne/releases/latest)**:

| File | What it's for |
|---|---|
| `ConfGoOne-x.x.x.exe` | No install, no admin rights — just run it |

Windows only for now, macOS in progress. It's a portable app, so check back here for new versions — there's no in-app update check yet.

<br>

## 💳 Licensing & pricing

| | Free | Pro | Enterprise |
|---|:---:|:---:|:---:|
| **Price** | $0 forever | $49/mo | $129/mo |
| Scans | 3, ever | 50/month | Unlimited |
| Compliance frameworks | CIS + NIST 800-53 | All 16 + custom/XCCDF | All 16 + custom/XCCDF |
| Report export | HTML | HTML, PDF, Word, Excel | HTML, PDF, Word, Excel |
| Cloud AI + validation pass | — | ✅ | ✅ |
| Drift detection + remediation PRs | — | ✅ | ✅ |
| Cyber Risk Quantification | — | ✅ | ✅ |
| Multi-tenant / MSP mode | — | — | ✅ |
| Support | Community | Priority email | Direct channel |

One license, activated on one machine. See the **[pricing page](https://confgoone.com/#pricing)** for current terms, discounts on longer billing cycles, and tax details.

<br>

## 🔒 Privacy & security

- Runs **entirely offline by default** — your configuration data never leaves your machine
- The only exception is whatever you explicitly send to your own AI provider, if you choose to turn that feature on
- No install-time telemetry
- License keys are bound to your machine, verified cryptographically, and never phone home

<br>

## 🤝 Support

Found a bug, or something not working as expected? Open an **[issue](https://github.com/Ma5t3r5hadw/ConfGoOne/issues)** here.

For licensing or billing questions, use the contact link on the **[website](https://confgoone.com/)**, or email **confgoone@gmail.com**.

<br>

<div align="center">

<sub>© <!-- year --> ConfGoOne. All rights reserved.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d121e,50:2f8ef4,100:8b7bff&height=100&section=footer" width="100%" alt="">

</div>
