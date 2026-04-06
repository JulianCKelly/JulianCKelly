# Julian Charlan Kelly

**Data Engineer / Analytics Engineer** focused on reliable pipelines, governed data models, and decision-ready analytics.

Los Angeles, CA · [LinkedIn](https://www.linkedin.com/in/juliancharlankelly/)

---

## About

I build data systems that hold up under scrutiny — clean staging layers, explicit grain definitions, defensible business logic, and documentation that explains *why*, not just *what*.

My background spans cell & molecular biology, clinical operations, and healthcare analytics. I bring domain fluency to data work in healthcare and beyond: I understand what the data means, not just how to move it.

I'm especially drawn to problems where correctness matters — FHIR-based clinical data, financial reporting pipelines, operational analytics — and where the difference between a working pipeline and a trustworthy one is worth caring about.

---

## Core Skills

**Data Engineering & Analytics Engineering**
- Pipeline design, transformation layers, and dimensional modeling (SQL / Python)
- dbt (models, tests, documentation, seeds, macros)
- Snowflake, PostgreSQL, DuckDB, BigQuery
- Fivetran, Airflow, dbt Cloud
- FHIR data standards and healthcare interoperability
- Parquet, JSON/XBRL ingestion, semi-structured data handling

**Data Quality & Governance**
- Defensive data handling: referential integrity, null propagation, deduplication logic
- Schema tests, singular tests, and business rule enforcement
- Explicit grain definition and precedence-based conflict resolution

**Machine Learning & Analytics**
- Supervised models: classification, risk prediction (recall-sensitive clinical contexts)
- Feature engineering, model evaluation (AUC, precision/recall tradeoffs)
- Clinically-informed decision support pipelines

**Tooling & Workflow**
- Git, CLI-based reproducible workflows
- Structured repository design and technical documentation
- Stakeholder translation: from ambiguous business questions to testable data models

---

## Featured Project

### SEC Fundamentals Pipeline — End-to-End Financial Data Engineering

Production-style pipeline ingesting raw SEC XBRL filings and producing a clean, deduplicated, analytics-ready fundamentals dataset across AAPL, MSFT, NVDA, JPM, and AMZN.

**Highlights:**
- Full pipeline: ingestion → flatten → standardize → deduplicate → mart
- Canonical metric mapping via seed file with priority-based tag resolution
- Four-level deduplication precedence: tag priority → segment preference → form type → filing recency
- Explicit grain separation: income statement (duration) vs. balance sheet (instant) metrics
- 69,171 raw rows → 63 mart rows. Zero remaining duplicate company-metric-period combinations.

**Repository:** https://github.com/JulianCKelly/sec-fundamentals-pipeline

---

## Additional Projects

### ClinicIQ Analytics Engineering

Analytics engineering project for healthcare cost estimation featuring production-style ingestion, validation, and analytics-ready modeling with FHIR-informed schema design and data quality controls.

Repo: https://github.com/JulianCKelly/cliniciq-analytics-engineering

---

### ICD/CPT Validator + Cost Estimator

Flask app validating ICD-10 and CPT codes against reference tables with cost estimation workflows. Structured backend with reproducible local setup and healthcare billing data integration.

Repo: https://github.com/JulianCKelly/icd-cpt-validator

---

## Current Focus

- Designing maintainable data pipelines and transformation layers at the senior level
- Applying analytics engineering patterns in healthcare and operational contexts
- Translating ambiguous business problems into testable, documented, production-ready workflows
