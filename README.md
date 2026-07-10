# Dexity Intel — JD Datasets & Methodology

Public verification data behind Dexity's career-guide articles at **[dexity.com/intel](https://dexity.com/intel)**. Each article links to **its own role's dataset** below — every percentage in the piece is computed from these real postings.

## Datasets (one per role · current scan)

| Role dataset | Backs article |
|---|---|
| [`data/product_manager.csv`](data/product_manager.csv) | Product Manager / AI PM |
| [`data/ai_engineer.csv`](data/ai_engineer.csv) | AI Engineer / What is an AI Engineer |
| [`data/engineering_manager.csv`](data/engineering_manager.csv) | Engineering Manager |
| [`data/marketing.csv`](data/marketing.csv) | The AI Marketer |
| [`data/forward_deployed.csv`](data/forward_deployed.csv) | Forward Deployed Engineer (+responsibilities, +bottleneck) |
| [`data/security_engineer.csv`](data/security_engineer.csv) | AI Security career |
| [`data/ai_infra_platform.csv`](data/ai_infra_platform.csv) | AI Infra / Platform Engineer |
| [`data/data_engineer.csv`](data/data_engineer.csv) | Data Engineer (upcoming) |
| [`data/sre_resilience.csv`](data/sre_resilience.csv) | SRE / Resilience (upcoming) |
| [`data/ai_governance.csv`](data/ai_governance.csv) | AI Governance (upcoming) |
| [`data/ai_leadership.csv`](data/ai_leadership.csv) | AI Leadership (upcoming) |
| [`data/ai_security_redteam.csv`](data/ai_security_redteam.csv) | AI Red Teaming (upcoming) |
| [`data/cloud_security.csv`](data/cloud_security.csv) | Cloud Security (upcoming) |

## Month-over-month scans (how the market is moving)

Each scan is **dated and archived** under `data/<YYYY-MM>/`, so the trend is checkable — not a one-time snapshot. When an article can compare two or more like-for-like scans, it shows the delta (e.g. the Forward Deployed Engineer pool: 187 → 399 → 451).

| Snapshot | Folder |
|---|---|
| July 2026 (baseline) | [`data/2026-07/`](data/2026-07/) |

The top-level `data/*.csv` files always hold the **latest** scan; the dated folders preserve each prior scan for month-over-month comparison. Comparisons are only drawn between scans coded the same way; where an earlier scan used a different method or board list, the article says so explicitly.

## Method
- **Source:** public applicant-tracking boards (Greenhouse, Lever, Ashby) via official JSON APIs — no scraping, no login.
- **Snapshot:** live at scan time. **Rolling scans** — counts change as roles open/close, so an April article and a July one can differ (e.g. Forward Deployed Engineer: 187 Apr → 399 May → 191 strict-title Jul).
- **Coding:** keyword-matched from full JD text; shares are **directional, not survey-grade**.
- **Salary:** only US-dollar disclosed bands counted; third-party comp aggregators are labeled directional in the articles, not first-party data.

*Contact: hello@dexity.com*
