# Data Loom HQ — Automated ETL Framework for High‑Fidelity Data Cleaning

## Overview

Data Loom HQ is a custom ETL (Extract, Transform, Load) application designed to automate the sanitization and structural organization of high‑volume datasets. Built in Python and originally deployed on Replit, the tool streamlines the data preparation phase for analytics workflows in SQL, Tableau, and Python/R environments.

> “Data is the thread, but a refined ETL process is the loom. By automating the cleaning phase with Data Loom HQ, we ensure the final business strategy is woven from the strongest possible evidence.”

This project began as a solution to recurring operational challenges in real‑world business environments, where inconsistent data formats, duplicates, and structural anomalies slowed down analysis. Data Loom HQ eliminates these bottlenecks.

---

## Core Features

### 🔹 Automated Sanitization
- Removes duplicate records  
- Standardizes column names  
- Normalizes numeric formats  
- Cleans price ranges, text fields, and whitespace  
- Ensures consistent date formatting  

### 🔹 SQL Syntax Generation
Automatically converts transformation logic into executable SQL statements for BigQuery or other SQL engines.

### 🔹 Trend & Outlier Detection
Identifies deep‑layer anomalies and performance outliers that standard spreadsheet tools often miss.

### 🔹 Reproducible Audit Trail
Every transformation is logged in a structured changelog for transparency and governance.

---

## Architecture

See `docs/architecture.md` for a breakdown of:

- ETL pipeline stages  
- Data validation logic  
- Syntax Track module  
- Error handling  
- Output structure  

---

## Example Use Cases

### Shopify 2025 Product Sales Analysis
Data Loom HQ was used to sanitize the raw Kaggle dataset before SQL benchmarking and Tableau visualization.

### Bellabeat Wearable Data Analysis
Used to validate and standardize activity, sleep, and weight logs before merging datasets.

More examples are available in the `examples/` folder.

---

## Screenshots

Screenshots of the UI, workflow, and output logs are available in the `screenshots/` directory.

---

## Changelog

A full audit trail of transformations is available in `docs/changelog.md`.

---

## Roadmap

- Add CLI interface  
- Add automated schema inference  
- Add export to Parquet/Feather  
- Add anomaly scoring module  

---

## Author

**Jerred Aldridge**  
Developer of Data Loom HQ  
