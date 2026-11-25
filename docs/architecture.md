# Telecom Data Platform Architecture

## 1. Overview

The Telecom Data Engineering Platform is built using Microsoft Fabric and PySpark. It processes telecom source datasets through a Medallion Architecture.

## 2. Architecture Layers

### Source Layer
Contains the original telecom datasets:
- Customers
- Subscriptions
- Network Sessions
- Call Detail Records (CDR)
- Network Towers

### Bronze Layer
- Ingests source data into Delta tables.
- Preserves raw data.
- Adds ingestion metadata.
- Validates record counts and primary keys.

### Silver Layer
- Cleans and transforms Bronze data.
- Applies data quality rules.
- Validates null values and duplicate records.
- Maintains data integrity.

### Gold Layer
- Produces analytics-ready datasets.
- Creates business-level aggregated tables.
- Validates record counts against Silver data.

### Quality Monitoring
- Monitors source, Bronze, Silver, and Gold tables.
- Checks record counts and data quality.
- Validates data integrity.
- Reports validation results.

## 3. Technology Stack

- Microsoft Fabric
- PySpark
- Python
- Delta Lake
- Lakehouse
- Medallion Architecture

## 4. Current Project Status

Bronze, Silver, Gold, and centralized quality monitoring have been completed and validated.

Production deployment documentation is pending.
