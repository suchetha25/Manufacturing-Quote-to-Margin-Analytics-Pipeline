# Manufacturing Quote-to-Margin Analytics Pipeline

An end-to-end, batch-processing data engineering pipeline built natively on the **Databricks Lakehouse Platform**. The project ingests quote and line-item data (simulating Oracle CPQ payloads), parses nested configurations, cleans transactions, and computes real-time gross margin metrics to detect profitability erosion across manufacturing product lines.

## Architecture & Tech Stack

**Processing Engine:** Apache Spark / PySpark
**Storage Layer:** Delta Lake (Medallion Architecture: Bronze -> Silver -> Gold)
**Orchestration:** Databricks Workflows (Multi-task DAG)
**Security & Governance:** Databricks Secrets & Unity Catalog
**Language:** Python, Spark SQL
