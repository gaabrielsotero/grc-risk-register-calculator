# GRC Risk Register Calculator

> **ISO 31000:2018 · DORA (EU 2022/2554) · NIST RMF · GDPR · FATF Recommendations**

A single-page interactive risk assessment tool built for EU-regulated financial services compliance contexts. Supports structured inherent-to-residual risk scoring, dual heat map visualisation, context-aware GRC recommendations, and CSV/JSON export.

**🔗 Live Demo:** https://gaabrielsotero.github.io/grc-risk-register-calculator

---

## Purpose

Built by a Compliance Analyst operating in EU AML/KYC and ICT risk regulatory environments to support structured, audit-ready risk assessments. The tool operationalises ISO 31000 methodology with regulatory overlays relevant to FinTech and banking compliance teams.

---

## Key Features

| Feature | Detail |
|---|---|
| **Inherent vs. Residual Scoring** | Correct ISO 31000 methodology: Residual = Residual Likelihood × Residual Impact |
| **Control Effectiveness Rating** | 3-tier scale (Strong / Partial / Weak-None) with visual feedback |
| **Dual Heat Map** | Side-by-side inherent and residual 5×5 matrix with risk plotted as dots |
| **Context-Aware Recommendations** | Engine generates GRC actions based on risk category + treatment + level |
| **Risk Register Table** | Full register with edit/delete, expandable GRC recommendation panels |
| **Export CSV / JSON** | 20-field export compatible with Excel, Google Sheets, and enterprise GRC tools |
| **ISO 27001:2022 Annex A Cross-Reference** | Each risk can be mapped to specific Annex A controls |
| **Dark / Light Mode** | Full theme toggle with persistent CSS variables |
| **Mobile Responsive** | Fully functional on tablet and mobile |

---

## Regulatory Framework Coverage

| Framework | Scope in Tool |
|---|---|
| **ISO 31000:2018** | Core risk assessment methodology, residual risk calculation |
| **DORA (EU 2022/2554)** | Art. 11 ICT continuity, Art. 28/30 third-party ICT risk |
| **GDPR** | Art. 32 security measures, Art. 35 DPIA trigger, Art. 12/15 DSAR |
| **EU AML Directive (AMLD6)** | Art. 18 EDD, FATF Rec. 10 CDD, MLRO escalation SLA |
| **FATF Recommendations** | Rec. 10 CDD, Rec. 18 AML programme, typology detection |
| **NIST RMF** | Risk treatment categories alignment |
| **ISO 27001:2022** | Annex A control reference mapping (A.5.x, A.8.x) |
| **NIS2 Directive** | Art. 21 security measures (IAM, MFA, access control) |

---

## Risk Scoring Methodology

Inherent Risk Score = Inherent Likelihood (1–5) × Inherent Impact (1–5)
Residual Risk Score = Residual Likelihood (1–5) × Residual Impact (1–5)

Risk Levels:
CRITICAL ≥ 16 → Mandatory escalation to CISO/CRO within 24h
HIGH 10–15 → Treatment plan required; Accept requires CRO approval
MEDIUM 5–9 → Standard treatment with documented owner
LOW 1–4 → Accept permissible with documented justification
