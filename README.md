# Revenue Hygiene & Forecasting System (Salesforce Admin Project)

## The Purpose of This Project

This project demonstrates advanced Salesforce Administration capabilities by designing and implementing a governance-driven revenue forecasting and pipeline health system.

The goal was to improve forecast reliability and pipeline integrity by combining:
- Flow Builder automation concepts
- Validation rules enforcing MEDDIC qualification standards
- Pipeline aging and risk logic
- Structured forecast modeling (weighted vs non-weighted)
- Executive-level dashboards for revenue decision-making

The system is designed to simulate a real-world RevOps environment where data quality, deal qualification, and pipeline discipline directly impact forecast accuracy and revenue predictability.

---

## What is Contained in the Assets Folder

The `Assets` folder contains all documentation and supporting visualization materials for this project.

Each dashboard is organized as follows:

- **2 Markdown files** describing:
  - Dashboard purpose and governance context
  - Key metrics and pipeline logic
  - Strategic insights derived from Salesforce opportunity and account data

- A **screenshots folder** containing images of all dashboard visualizations referenced in the Markdown file

Each Markdown file represents a single dashboard and provides a self-contained breakdown of both analytical outputs and supporting visual evidence.

---

## The TLDR of Each Markdown File

### 1. Revenue Forecast & Rep Performance Hub

This dashboard provides an executive-level forecasting and performance view of the revenue pipeline, combining stage progression, forecast categories, and rep-level contribution analysis.

#### Top Insights

- **Forecast accuracy improves when combining weighted and unweighted pipeline views**
  - Using both models reduces optimism bias and provides a more realistic view of expected revenue performance.

- **Pipeline progression is uneven across forecast categories**
  - A significant portion of revenue remains in early-stage categories, indicating inconsistent deal advancement discipline.

- **Stage concentration reveals bottlenecks in revenue flow**
  - Certain pipeline stages accumulate disproportionate value, signaling inefficiencies in conversion or qualification processes.

- **Rep performance is highly variable and impacts revenue predictability**
  - Pipeline ownership is unevenly distributed, creating both concentration risk and opportunities for coaching and standardization.

- **Weighted forecasting provides stronger executive decision support**
  - Probability-adjusted metrics offer a more reliable foundation for revenue planning and quota tracking than raw pipeline totals alone.

---

### 2. Pipeline Aging & Health Monitor

This dashboard provides a pipeline governance and risk management view focused on deal aging, qualification quality, and opportunity health across the sales funnel.

#### Top Insights

- **Pipeline visibility alone is not enough without health classification**
  - Segmenting opportunities into health categories (Healthy, Watch, Aging, Critical) is essential for prioritization and risk management.

- **Aging pipeline is a leading indicator of revenue risk**
  - Stalled or long-aged opportunities signal future forecast volatility and require proactive intervention before close dates approach.

- **At-risk pipeline tracking enables proactive revenue recovery**
  - Identifying and managing high-risk deals improves forecast reliability and reduces avoidable revenue leakage.

- **MEDDIC compliance directly improves forecast integrity**
  - Opportunities lacking qualification discipline reduce confidence in pipeline accuracy and should be addressed before progression.

- **Pipeline governance improves cross-functional alignment**
  - A shared health and risk framework ensures consistent decision-making across sales leadership, RevOps, and frontline managers.

---
