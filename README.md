# Julian Charlan Kelly

**Senior Data Engineer** — FHIR, HL7, cross-border clinical data infrastructure · Snowflake · dbt · Python

Los Angeles, CA · [LinkedIn](https://www.linkedin.com/in/juliancharlankelly/)

---

## About

I build data systems that can stand up to scrutiny: clean staging layers, clear grain definitions, defensible business logic, and documentation that explains why, not just what.
My path here wasn't linear. I started pre-med at Augusta University and made it through the hard science sequence: organic chemistry, biochemistry, microbiology, physics, before switching majors junior year. Then years in regulated clinical environments before moving into data engineering. Healthcare data isn't a domain I picked up for a role. The science came first.
I care about correctness. FHIR-based clinical data, financial reporting pipelines, operational analytics. The work I'm drawn to is the kind where the difference between a pipeline that runs and one that can be trusted actually matters.

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

Healthcare analytics engineering project demonstrating production-style patterns for ingesting, validating, and modeling synthetic EMR-style data into analytics-ready datasets using dbt, DuckDB, and FastAPI.

Repo: https://github.com/JulianCKelly/cliniciq-analytics-engineering

---

### ICD/CPT Validator + Cost Estimator

Flask app validating ICD-10 and CPT codes against reference tables with cost estimation workflows. Structured backend with reproducible local setup and healthcare billing data integration.

Repo: https://github.com/JulianCKelly/icd-cpt-validator

---

## Current Focus

- Applying analytics engineering patterns in healthcare and operational contexts
- Translating ambiguous business problems into testable, documented, production-ready workflows
