# Zinnia Process Engineering Intern — Portfolio Projects

**Candidate:** Vivek Kumar | TISS Analytics PG | m2025anl036@stud.tiss.ac.in
**Target Role:** Process Engineering Intern — Zinnia (Insurance Technology)

---

## Project Architecture

```
zinnia_process_engineering/
├── 01_sop_process_mapping/
│   └── SOP_Process_Mapping_Analysis.ipynb        ← Project 1
├── 02_productivity_quality_dashboard/
│   └── Productivity_Quality_KPI_Dashboard.ipynb   ← Project 2
├── 03_data_reconciliation_pipeline/
│   └── Data_Reconciliation_Pipeline.ipynb         ← Project 3
├── 04_customer_retention_analytics/
│   └── Customer_Retention_PostIssue_Analytics.ipynb ← Project 4
└── README.md
```

---

## Project 1 — Process Mapping & SOP Documentation for Multi-Step Service Operations

| | |
|---|---|
| **Domain** | Operations & Quality Management |
| **Role Context** | Barbeque Nation – Assistant Manager, Operations & L&D |
| **Tools** | Python (Pandas, Matplotlib, Seaborn), Value Stream Mapping, Audit Checklists |
| **JD Keywords** | Value Stream Mapping, SOP authoring, process workflows, compliance audit, error-rate reduction |

**What it covers:**
- Synthesises a 180-day, 3-shift operational audit dataset (6 stations × 3 shifts)
- Maps current-state and future-state service delivery workflows (SIPOC)
- Pareto analysis of error rates by station — identifies top 3 defect sources
- Compliance score distribution: Pre-SOP (mean 65) → Post-SOP (mean 87)
- Customer complaint trend showing ~20% reduction post-rollout
- Error heatmap by station × shift for targeted corrective action

---

## Project 2 — Productivity & Quality KPI Monitoring Dashboard

| | |
|---|---|
| **Domain** | Process Performance & MIS Reporting |
| **Role Context** | BJT Global / Jio Platforms – Process & Predictive Analyst |
| **Tools** | Python (Pandas, Matplotlib, Seaborn), Power BI (replicated), DAX-style alerts |
| **JD Keywords** | Productivity & Quality evaluation, TAT tracking, SLA compliance, KPI dashboards |

**What it covers:**
- 90-day analyst × shift × queue performance dataset (12 analysts, 4 queues)
- 4-panel KPI dashboard: Productivity by shift, Rework rate by queue, Weekly TAT trend, SLA breach by analyst
- Analyst × queue TAT adherence heatmap
- Backlog size tracking with threshold alerts (>15 items triggers rebalancing)
- Automated SLA breach alert logic (flags weeks where breach rate >15%)

---

## Project 3 — Automated Data Reconciliation & Error-Rate Reduction Pipeline

| | |
|---|---|
| **Domain** | Data Engineering & Process Automation |
| **Role Context** | OrgaKnow / Jio Platforms – Data Science & Process-Optimisation Intern |
| **Tools** | Python (Pandas, NumPy), Rule-based validation engine, Exception log |
| **JD Keywords** | Data collection & analysis, error-rate reduction, process workflows, technical specifications |

**What it covers:**
- Simulates 4 messy data sources (CRM, ERP, Portal, Legacy) with intentional errors
- Pre-reconciliation error profiling: missing IDs, duplicates, format violations, range anomalies
- 5-rule automated reconciliation engine with a structured exception log
- Error rate reduced from ~16.5% → <1% (manual effort reduced ~60%)
- Source quality audit: before/after comparison per source
- Outputs clean CSV + exception log CSV for rework routing

---

## Project 4 — Customer Retention & Post-Issue Friction Analytics

| | |
|---|---|
| **Domain** | Insurance / Fintech — Claims & Post-Issue Improvement |
| **Role Context** | Directly aligned to Zinnia's post-issue mandate |
| **Tools** | Python (Pandas, Scikit-learn, Matplotlib, Seaborn), ML pipeline |
| **JD Keywords** | Post-issue, claims, friction analysis, cross-functional, continuous improvement |

**What it covers:**
- 8,000-policyholder synthetic dataset with realistic friction features (billing disputes, claims denied, payment failures, NPS, support tickets)
- Feature engineering: TotalFrictionScore, NPS_Category, HighRisk_Flag, Tenure_Band
- EDA dashboard (6 panels): churn by PolicyType, BillingMode, NPS, support tickets, payment failures, CLV scatter
- ML Tournament: Logistic Regression vs Random Forest vs Gradient Boosting (CV + test evaluation)
- ROC curve, PR curve, confusion matrix, classification report
- Feature importance: claims denied + support tickets = top churn drivers
- Risk segmentation (Low / Medium / High / Critical) + proactive outreach list export

---

## How to Run

```powershell
# Activate the shared venv
d:/Resume/projects/.venv/Scripts/Activate.ps1

# Launch Jupyter
jupyter notebook

# Open notebooks in browser — all outputs are pre-built, just run cells
```

---

## Interview Pitch — Zinnia Alignment

> *"My four Zinnia projects mirror the exact workflows described in the JD. Project 1 demonstrates end-to-end VSM and SOP documentation from my Barbeque Nation role. Project 2 replicates the KPI dashboards I built at BJT Global and Jio. Project 3 shows the data reconciliation automation I built at OrgaKnow. Project 4 models Zinnia's specific post-issue and claims-friction challenge using ML segmentation."*
