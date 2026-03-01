# Azure Databricks Medallion Architecture – F1 Racing Data Pipeline

## 📌 Project Overview
This project implements an end-to-end Data Engineering pipeline using **Azure Databricks** and **PySpark**, following the **Medallion Architecture (Bronze, Silver, Gold layers)**.

The pipeline processes Formula 1 racing datasets sourced from Kaggle and transforms raw data into curated analytical tables suitable for reporting and analytics.

---

## 🏗 Architecture
Source (CSV files from Kaggle)  
→ Bronze Layer (raw ingestion)  
→ Silver Layer (cleansing & standardization)  
→ Gold Layer (business transformations & dimensional modeling)

---

## ⚙️ Tech Stack
- Azure Databricks  
- PySpark  
- Delta Lake  
- Azure Data Factory (for orchestration & triggers)  
- GitHub (version control)

---

## 📂 Project Structure
