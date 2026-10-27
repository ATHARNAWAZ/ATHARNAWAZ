# Ather Nawaz

**AI Data Engineer in Ingolstadt, Germany.** I build data systems that catch their own failures and explain them.

- **In production (SCA Logistics & Fulfilment, since 2019):** I designed and run the company's whole data platform: Azure Data Factory, ADLS Gen2, Databricks with Delta Lake, PySpark, dbt and Unity Catalog, about 300,000 records a day. Statistical anomaly detection and alerting catch problems before anyone opens a report: no silent pipeline failures since 2022.
- **In my own open-source work:** LLM systems on top of data. Retrieval, lineage and guardrails, because the data an LLM is given is where most AI problems start.

🌐 [atharnawaz.github.io](https://atharnawaz.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/atharnawaz) · ✉️ atharnawaz@live.com

---

## Featured work

| Project | What it does | Stack |
|---|---|---|
| [**Pipeline Doctor**](https://github.com/ATHARNAWAZ/pipeline-doctor) | Reads a failed dbt run, traces the lineage, retrieves the relevant SQL with RAG and explains the root cause in plain English. Optional Slack alerts via AWS Lambda. | FastAPI, NetworkX, LlamaIndex, pgvector, LLM API, React |
| [**Meridian**](https://github.com/ATHARNAWAZ/meridian) | Real-time e-commerce analytics: event-time watermarks, late events, exactly-once into Iceberg, Flink CEP fraud detection. One `make demo`. | Kafka + Avro, Flink, Iceberg, dbt, DuckDB, Prometheus, Grafana |
| [**quarantine-dq**](https://github.com/ATHARNAWAZ/quarantine-dq) | Bad records are quarantined with their failure reason and replayed after a fix, instead of crashing the pipeline or disappearing. 82 tests. | Python, DuckDB/Postgres, pandas/Spark/Airflow/dbt adapters |
| [**dbt-contracts**](https://github.com/ATHARNAWAZ/dbt-contracts) | LLM-generated data contracts for every dbt model, enforced on each PR by a GitHub Action. [Live app](https://dbt-contracts.vercel.app) | FastAPI, React, LLM API, GitHub Actions |
| [**dbt Lineage Explorer**](https://github.com/ATHARNAWAZ/dbt-lineage-explorer) | Interactive DAG with column-level lineage and an AI impact analysis before you ship. [Live app](https://dbt-lineage-explorer.vercel.app) | NetworkX, React Flow, FastAPI |
| [**BookWorm Data Platform**](https://github.com/ATHARNAWAZ/bookworm-data-platform) | Medallion lakehouse on Azure Databricks over 2.3M books and 15.7M reviews. | Databricks, Delta Lake, dbt, Unity Catalog |

---

## Tools, sorted honestly

**Every day in production:** Python · SQL · PySpark · dbt · Databricks · Delta Lake · Unity Catalog · Azure Data Factory · ADLS Gen2 · SQL Server · Power BI · GitHub Actions · Docker · FastAPI

**AI, in my projects:** RAG · embeddings · pgvector · LlamaIndex · LangChain · LLM APIs (OpenAI, Anthropic) · MCP

**Data, in my projects:** Kafka · Flink · Apache Iceberg · DuckDB · Airflow · Dagster · Snowflake · AWS (S3, Glue, Athena, Lambda) · Prometheus · Grafana · Terraform

---

## Certifications

| Certification | Status |
|---|---|
| [Databricks Fundamentals](https://credentials.databricks.com/6640237a-cbe5-4f1c-a55f-c011602e69e6) | ✅ March 2026 |
| Databricks Data Engineer Associate | In progress |
| dbt Analytics Engineering | In progress |
| Snowflake SnowPro Core | In progress |

---

Open to permanent **AI Data Engineer** and **Senior Data Engineer** roles in Munich, remote in Germany, or with relocation. German citizen. English C2, German B1 (telc).
