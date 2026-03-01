# Azure Databricks Medallion Architecture – F1 Racing Data Pipeline

## 📌 Project Overview
This project implements an end-to-end Data Engineering pipeline using **Azure Databricks** and **PySpark**, following the **Medallion Architecture (Bronze, Silver, Gold layers)**.

The pipeline processes Formula 1 racing datasets sourced from Kaggle and transforms raw data into curated analytical tables suitable for reporting and analytics.

---

## 🏗 Architecture
Source (CSV/JSON files from Kaggle)  
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

---

## 🟤 Bronze Layer (Raw Ingestion)
- Ingests raw CSV files into Delta tables  
- Minimal transformations applied  
- Preserves original structure for traceability  
- Acts as the raw data landing zone  

---

## ⚪ Silver Layer (Cleansed & Refined)
- Handles data quality and standardization  
- Deduplication of records  
- Implements incremental data loading  
- Prepares datasets for analytical transformations  

---

## 🟡 Gold Layer (Business & Analytics)
- Applies business logic and transformations  
- Implements Slowly Changing Dimension (SCD Type 2)  
- Builds curated analytical tables  
- Designed for reporting and downstream consumption  

---

## 🔁 Orchestration
- Pipeline execution is controlled using a master orchestration notebook  
- Azure Data Factory triggers are used to schedule and automate pipeline runs  
- Ensures Bronze → Silver → Gold execution order  

---

## 🚀 Key Features
- Medallion Architecture implementation  
- Modular notebook design  
- Delta Lake storage format  
- Incremental data processing  
- SCD Type 2 handling for dimensional data  
- GitHub-based version control  

---

## 📊 Dataset
Formula 1 racing dataset sourced from Kaggle, containing:
- Drivers  
- Constructors  
- Race results  
- Lap times  
- Standings  

---

## 🔮 Future Enhancements
- Add data quality checks and validation rules  
- Implement performance optimizations (partitioning, Z-ORDER)  
- Integrate with Power BI for visualization  
- Add CI/CD using GitHub Actions  
- Add unit testing for transformations  

---

## 👤 Author
Rohith Kanumuri

This project was built as a hands-on Data Engineering implementation to demonstrate practical usage of Azure Databricks, PySpark, and Medallion Architecture.
