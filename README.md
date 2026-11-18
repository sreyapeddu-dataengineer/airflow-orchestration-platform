# Airflow-Orchestrated ELT with Data Quality — Airflow, Great Expectations & CI/CD

Production-style orchestration for batch and streaming ELT using Apache Airflow, with DAG design, dependency management, SLA alerts, retry logic and backfills. Data quality is built in through Great Expectations validation and dbt tests, and pipelines are delivered through GitHub Actions CI/CD with unit and pipeline testing. Patterns reflect Cloud Composer-style managed Airflow and production support with root-cause analysis.

**Tech stack:** Apache Airflow • Python • Great Expectations • GitHub Actions • Docker

## Architecture Overview
DAGs schedule and order ELT tasks → validation gates (Great Expectations / dbt tests) block bad data → SLA alerts and retries handle failures → CI/CD promotes tested DAGs across dev / UAT / prod.

## Project Structure
`dags/, plugins/, include/, tests/`

## How to Run
Start Airflow locally (standalone or Docker), enable a sample DAG in dags/, and trigger it to see retries, validation gates and alerting hooks run.

## Skills Demonstrated
Apache Airflow, Cloud Composer, Python, Workflow Automation, Great Expectations, dbt Tests, Data Quality / Validation, GitHub Actions, CI/CD, Pipeline Monitoring & Observability, SLA Alerts, Retry Logic & Backfills, Incident Management / RCA

## Notes
Portfolio project built on **synthetic data only** — real production engineering patterns from healthcare and financial services data engineering, with no real patient, customer, or market data, and no employer-confidential code or data.

---
*By Sreya Peddu — Senior Data Engineer, Dallas–Fort Worth, TX • peddusreya02@gmail.com • [LinkedIn](https://www.linkedin.com/in/sreyapeddu)*
