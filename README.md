# Dexity Intel — JD Datasets & Methodology

Public verification data behind Dexity's career-guide articles at **[dexity.com/intel](https://dexity.com/intel)**. Each article links to **its own role's dataset** below — every percentage in the piece is computed from these real postings.

## Datasets (one per role · July 2026 scan)

| Role dataset | Postings | Backs article |
|---|---|---|
| [`data/ai_engineer.csv`](data/ai_engineer.csv) | 390 | AI Engineer / What is an AI Engineer |
| [`data/ai_governance.csv`](data/ai_governance.csv) | 48 | AI Governance (upcoming) |
| [`data/ai_infra_platform.csv`](data/ai_infra_platform.csv) | 71 | AI Infra / Platform Engineer |
| [`data/ai_leadership.csv`](data/ai_leadership.csv) | 30 | AI Leadership (upcoming) |
| [`data/ai_security_redteam.csv`](data/ai_security_redteam.csv) | 41 | AI Red Teaming (upcoming) |
| [`data/cloud_security.csv`](data/cloud_security.csv) | 22 | Cloud Security (upcoming) |
| [`data/data_engineer.csv`](data/data_engineer.csv) | 173 | Data Engineer (upcoming) |
| [`data/engineering_manager.csv`](data/engineering_manager.csv) | 345 | Engineering Manager |
| [`data/forward_deployed.csv`](data/forward_deployed.csv) | 451 | Forward Deployed Engineer (+responsibilities, +bottleneck) |
| [`data/marketing.csv`](data/marketing.csv) | 307 | The AI Marketer |
| [`data/product_manager.csv`](data/product_manager.csv) | 654 | Product Manager / AI PM |
| [`data/security_engineer.csv`](data/security_engineer.csv) | 191 | AI Security career |
| [`data/sre_resilience.csv`](data/sre_resilience.csv) | 213 | SRE / Resilience (upcoming) |

## Method
- **Source:** public applicant-tracking boards (Greenhouse, Lever, Ashby) via official JSON APIs — no scraping, no login.
- **Snapshot:** July 2026, live at scan time. **Rolling scans** — counts change as roles open/close, so an April article and a July one can differ (e.g. Forward Deployed Engineer: 187 Apr → 399 May → 191 Jul strict-title).
- **Coding:** keyword-matched from full JD text; shares are **directional, not survey-grade**.
- **Salary:** only US-dollar disclosed bands counted; third-party comp aggregators are labeled directional in the articles, not first-party data.

*Contact: hello@dexity.com*