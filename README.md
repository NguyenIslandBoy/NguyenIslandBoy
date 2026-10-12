# Hi, I'm Hoang Nguyen Lai 👋

**Analytics Engineer & Data Engineer** · MSc Data Science, Newcastle University (2026) · Microsoft Certified: Fabric Data Engineer (DP-700) & Analytics Engineer (DP-600)

I build the data layer teams rely on: ingestion pipelines, tested dbt models, governed semantic models and the CI that keeps them honest. Two years of commercial data work (27+ enterprise BI projects, 25+ freelance data solutions, a production ingestion pipeline in a SaaS team), then an MSc in the UK.

🎯 **Next:** AI / MLOps / Platform Engineering. I want to build the infrastructure that takes models from notebook to production: reliable pipelines, model serving, orchestration, CI/CD and observability.

## 🔧 Stack

**Analytics engineering:** dbt (models, tests, point-in-time marts), dimensional modelling, Power BI / Fabric semantic models (DAX, TMDL, Direct Lake, RLS), data dictionaries & lineage
**Data engineering:** Python, SQL (BigQuery, PostgreSQL, DuckDB, T-SQL), PySpark, medallion architecture, REST-API ingestion, Prefect, Airflow, Fabric Lakehouse/Warehouse
**MLOps & platform (growing):** FastAPI, Docker, GitHub Actions, Prefect-orchestrated model pipelines, LLM routing & fallback, Ollama, Claude Code + MCP
**Cloud:** Google Cloud (BigQuery, GCS), Azure / Microsoft Fabric

## 📂 Analytics & data engineering

| Project | Highlights |
| --- | --- |
| [**eCommerce Trading Engine**](https://github.com/NguyenIslandBoy/ecommerce-trading-engine) | Point-in-time-correct metric spine over 12 months of D2C data; 20 dbt models, 94 data tests; detectors separate real movement from measurement artifacts |
| [**NHS Urgent Care Analytics**](https://github.com/NguyenIslandBoy/nhs-uec-analytics) | dbt warehouse built to survive trust mergers, metric changes and restatements; merger lineage across 668 organisations, 41 tests |
| [**Insurance Pricing Pipeline**](https://github.com/NguyenIslandBoy/insurance-pricing) | Medallion pipeline over 678k policies: dbt Silver layer, PySpark features, 29 dbt + 58 PySpark tests running in CI on every push |
| [**Stack Overflow Survey Warehouse**](https://github.com/NguyenIslandBoy/stack-overflow-dev-survey) | 360k responses across 5 years; 170+ schema changes harmonised into one schema with data dictionary and lineage |
| [**Customer Journey Anomaly Detector**](https://github.com/NguyenIslandBoy/customer-journey-anomaly-detector) | GA4-on-BigQuery monitoring that flags spikes, conversion drops and untagged traffic before they hit reporting |

## 🚀 Towards MLOps & platform

| Project | Highlights |
| --- | --- |
| [**Insurance Pricing Pipeline**](https://github.com/NguyenIslandBoy/insurance-pricing) | GLM/LightGBM models served via FastAPI with Prefect orchestration and health checks |
| **BI Accelerator Plugin** (private) | Build & release system packaging Claude Code + MCP tooling as an installable plugin; 62 tests, SHA-stamped versioned releases |
| [**IELTS Daily Habit**](https://ieltsdailyhabit.com) | Live production app with multi-provider LLM routing, automatic fallback and versioned prompts |
| [**TrustLens**](https://github.com/NguyenIslandBoy/TrustLens) | Local Llama 3.1 batch extraction pipeline; 98% success with confidence guards and CI |

## 💼 Experience

- **Data Analytics Specialist, Secomus Technology** (2025): scheduled Python/SQL ETL from Crisp, Mixpanel and GA4 APIs into MySQL; designed the Docker + Airflow version for scale; 90–95% fewer manual data errors
- **BI Developer, freelance** (2024–25): 25+ data solutions; migrated client reporting onto governed Fabric Lakehouse/Warehouse
- **Data Analyst, MCI Solutions** (2024–25): led 27+ Fabric/Power BI projects; built automated data-validation and a three-server sync system

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hoang-nguyen-lai-a42925248/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:nguyenhoang15869@gmail.com)
[![Power BI Portfolio](https://img.shields.io/badge/Power%20BI%20Portfolio-F2C811?style=flat&logo=powerbi&logoColor=black)](https://power-bi-portfolio-one.vercel.app/)
