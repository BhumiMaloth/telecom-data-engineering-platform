# Telecom Data Engineering Platform

## Project Overview

This project demonstrates an end-to-end Telecom Data Engineering solution built using Microsoft Fabric and PySpark.

The platform processes telecom data through a structured Medallion Architecture, transforming raw source data into reliable, analytics-ready datasets with data quality validation and monitoring.

## Technology Stack

- Microsoft Fabric
- PySpark
- Python
- SQL
- Lakehouse
- Delta Lake
- Medallion Architecture (Bronze, Silver, Gold)
- GitHub

## Architecture

The project follows a Medallion Architecture:

1. **Source Layer** — Telecom source datasets.
2. **Bronze Layer** — Raw data ingestion into Delta tables.
3. **Silver Layer** — Data cleaning, transformation, and quality validation.
4. **Gold Layer** — Business-ready aggregated datasets.
5. **Quality Monitoring** — Validation of record counts, primary keys, metadata, and data integrity.

## Telecom Data Domains

The project includes datasets covering:

- Customers
- Subscriptions
- Network Sessions
- Call Detail Records (CDR)
- Network Towers

## Data Quality and Validation

Validation checks include:

- Source-to-Bronze record count reconciliation
- Bronze-to-Silver record count validation
- Null primary key checks
- Duplicate key checks
- Required metadata validation
- Data integrity checks
- Layer-level quality audits

## Project Status

- [x] Source data preparation
- [x] Bronze layer ingestion and validation
- [x] Silver layer transformations and quality audits
- [x] Gold layer completion and validation
- [x] Centralized monitoring and final validation
- [ ] Production deployment documentation

*Project status will be updated as each phase is completed and validated.*

## Author

**Bhumi Maloth**

Data Engineering | Microsoft Fabric | PySpark | SQL
