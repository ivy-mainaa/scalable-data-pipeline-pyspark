# Scalable-data-pipeline-pyspark
Production-style PySpark data pipeline implementing a Bronze–Silver–Gold architecture to transform raw e-commerce event data into analytics-ready business metrics.

---

## Architecture

- **Bronze:** Raw ingestion with enforced schema + partitioned Parquet storage  
- **Silver:** Data cleaning and validation (business rules applied)  
- **Gold:** Aggregated KPIs for reporting (revenue, conversion metrics, breakdowns)

---

## Key Outputs (Gold Layer)

- Daily revenue
- Daily conversion rate
- Revenue by device type
- Conversion by traffic source

> Note: Synthetic data is used to simulate production event logs.  
> In a real system, data would be sourced from cloud storage or streaming platforms.

---

## Project Structure

```
notebooks/ → End-to-end pipeline notebook
images/ → Project visuals
README.md → Documentation

```
---

## How to Run

1. Open the notebook in **Google Colab**
2. Run all cells from top to bottom
3. The pipeline generates synthetic event data and produces Bronze, Silver, and Gold layer outputs

---

## Tech Stack

- PySpark
- Parquet
- Google Colab

