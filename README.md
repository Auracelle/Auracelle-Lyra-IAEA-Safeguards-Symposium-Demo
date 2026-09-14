# Auracelle Lyra — Wargaming Demo

**Safeguards Governance Ecosystem & Legal Agreement Stress-Test Platform**

*Auracelle AI Governance Labs LLC · Grace-Alice Evans, Founder & Principal Investigator*

---

## Overview

Auracelle Lyra is a multi-domain governance simulation platform designed to stress-test whether policies, treaties, and legal agreements can sustain verification confidence under cross-domain disruption. This repository contains the **Wargaming Demo** — a self-contained HTML file with login authentication and a 40-step Agentic AI guided walkthrough covering all simulation sections.

The platform is calibrated against the **IAEA Safeguards Implementation Report for 2025** and the Iran–Hormuz crisis sequence (June 2025 – 2026), which produced the first formally documented loss of continuity of knowledge over a state's nuclear material stockpile in the IAEA's modern verification history.

---

## Repository Contents

```
auracelle-lyra-demo/
│
├── index.html          # Wargaming Demo (login + full simulation)
├── README.md           # This file
└── .gitignore
```

> **Single-file deployment.** The entire demo — login, simulation, AI walkthrough engine, audio narration, governance network visualisation, compliance convergence chart, and PSTOA outcomes assessment — is self-contained in `index.html`. No build step, no server, no dependencies beyond a modern browser.

---

## Access

| Credential | Value |
|---|---|
| Email | Any valid email address |
| Password | `Lyra2026` |
| Demo bypass | Click **"Continue as Demo User"** — no credentials required |

> The demo bypass button launches the full simulation and automatically starts the Agentic AI walkthrough.

---

## Agentic AI Guided Walkthrough

The walkthrough is a **40-step guided tour** with:

- **Typewriter narration** — text appears progressively as the agent speaks
- **Audio narration** — Web Speech API reads each step aloud (toggle with 🔊 button)
- **Speed control** — 0.5×, 1×, 1.5×, 2× playback speed
- **Element highlighting** — the section being discussed is outlined with a purple pulse
- **Contextual tooltips** — floating tooltip appears near each highlighted element
- **Floating Next bar** — fixed bottom-right navigation so you never scroll back to top
- **Tab auto-switching** — the agent switches tabs automatically as it progresses

### Walkthrough Coverage

| Section | Steps |
|---|---|
| Introduction & Platform Overview | 1 |
| Domain Selector & g-GWC Score | 2 |
| Game State (P_t, A_t, C_t, V_t, R_t) | 6 |
| Your Role / Standard / Country selectors | 3 |
| Governance Indicator Registry | 2 |
| Governance Capability Dimensions | 4 |
| Governance Network (IAEA SIR 2025 nodes) | 1 |
| Compliance Convergence (6-domain cascade) | 2 |
| Proliferation Pathways | 2 |
| Actions & Shocks (Iran calibration demo) | 3 |
| Governance Agreement Workbench | 4 |
| Country Wargaming | 3 |
| Assurance Stress-Test (all 6 sub-tabs) | 6 |
| Conclusion | 1 |

---

## Simulation Sections

### Governance Ecosystem & Legal Agreement
**E-AGPO-HT Engine** — Evans Accelerated Governance Policy Optimization, Hierarchical Theory

| Tab | Description |
|---|---|
| Game State | Five governance state vectors (P_t, A_t, C_t, V_t, R_t) with compliance gap detection |
| Governance Indicators | Quantitative inputs, normalised 0–1, with weakest-link override |
| Capability Dimensions | Seven aggregated governance capability scores |
| Governance Network | Animated IAEA SIR 2025 compliance network (10 named actors) |
| Compliance Convergence | 6-domain trajectory chart with Iran–Hormuz event markers |
| Proliferation Pathways | Domain-specific governance failure → proliferation pathway mapping |
| Actions & Shocks | Iran calibration scenario with weakest-link collapse demonstration |
| Outcomes Assessment | Live PSTOA scoring with treaty performance metrics |

### Governance Agreement Workbench
Upload any policy, treaty, or legal framework and score it for **Presence**, **Specificity**, and **Enforceability** against the Hormuz governance baseline (UNCLOS Part III + ECT Article 7 + INFCIRC/153).

### Country Wargaming
Compare two states' governance postures across all domain indicators. Loads pre-calibrated profiles including the Iran 2025 calibration.

---

## Calibration Basis

| Source | Role in Platform |
|---|---|
| IAEA SIR 2025 (published 15 July 2026) | Formal CoK loss validation; Iran compliance scores |
| IAEA GOV/2026/8 (27 February 2026) | Inspector access denial documentation |
| UNCTAD Hormuz Report (March 2026) | Energy cascade; cross-domain interdependency |
| NPT Article III / INFCIRC/153 / INFCIRC/540 | Treaty baseline and enforceability scoring |
| UNSCR 2231 | JCPOA verification framework collapse |

---

## Intellectual Property

The E-AGPO-HT and E-AGSO-HT frameworks, all indicator taxonomies, scoring architectures, and the Quantum Optimization Layer (LyraQ) are proprietary intellectual property of Auracelle AI Governance Labs LLC.

USPTO Provisional Applications:
- No. 64/108,020 (filed 9 July 2026)
- No. 64/108,101 (filed 9 July 2026)
- No. 19/768,839 (filed 7 August 2026)

This demo is provided for review purposes only. The detailed mathematical architecture, indicator weights, transformation functions, and BGC taxonomy identifiers are not disclosed in this public demonstration.

---

## Affiliations

- **Non-Resident Senior Fellow** — UC Berkeley Center for Long-Term Cybersecurity (CLTC)
- **Technical Role Member** — NATO STO SAS-219 (WinterStorm2030)
- **Doctoral Candidate** — Bath Spa University (Dr. John Curry, DoS)
- **Accepted Paper** — IAEA Safeguards Symposium 2026, Abstract #24, Track 3.5

---

## Technical Notes

- **No server required.** Open `index.html` directly in a browser, or serve with any static file server.
- **No data uploaded.** Document scoring runs entirely in-browser using keyword-overlap heuristics.
- **Audio requires browser permission.** Web Speech API uses the browser's built-in TTS engine. Chrome and Edge have the best voice selection. Firefox and Safari are supported.
- **Canvas visualisations** (Governance Network, Compliance Convergence) require an HTML5-capable browser. Tested in Chrome 126+, Edge 126+, Firefox 128+, Safari 17+.

---

*© 2026 Auracelle AI Governance Labs LLC. All Rights Reserved.*
