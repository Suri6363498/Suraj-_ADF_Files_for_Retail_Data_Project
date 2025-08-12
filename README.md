# azure-data-engineering-pipeline
End-to-end Azure Data Engineering pipelines using Azure Data Factory, Databricks (PySpark), ADLS, Delta Lake, and CI/CD deployment automation.

# 🚀 Azure Data Engineering Pipeline

**Author:** Suraj Korishetti  
**Role:** Azure Data Engineer | Big Data Engineer | ETL Developer  

---

## 📌 Overview
This project demonstrates an **end-to-end Azure Data Engineering workflow** designed for **scalable, high-performance data processing**.  
It integrates **Azure Data Factory**, **Azure Databricks**, **PySpark**, **ADLS**, **Delta Lake**, and **Azure SQL** to automate ingestion, transformation, and storage of large datasets.  

---

**Data Flow:**
1. **Ingest** – Pulls data from SQL, Oracle, SAP, and ADLS into Azure Data Lake Storage.  
2. **Transform** – Processes & cleans data using PySpark in Azure Databricks.  
3. **Load** – Stores curated datasets into Delta Lake & Azure SQL for analytics.  
4. **Automate** – Deploys pipelines via CI/CD with Azure DevOps.  

---

## ✨ Features
- ⚡ **Multi-source ingestion** – SQL, Oracle, SAP, ADLS  
- 🛠 **PySpark transformations** – Data cleaning, validation, and optimization  
- 💾 **Delta Live Tables** – Real-time data processing  
- 🔄 **CI/CD automation** – Azure DevOps deployment pipelines  
- 📊 **Analytics-ready data** – For Power BI & downstream systems  

---

## 🖥 Tech Stack
| Category | Tools |
|----------|-------|
| Cloud Platform | Microsoft Azure |
| Data Integration | Azure Data Factory |
| Processing Engine | Azure Databricks (PySpark, Spark SQL) |
| Storage | Azure Data Lake Storage, Delta Lake, Azure SQL Database |
| DevOps | Azure DevOps (CI/CD) |
| Visualization | Power BI |

---

## 📂 Project Structure
```plaintext
azure-data-engineering-pipeline/
│── README.md
│── architecture-diagram.png
│── code/
│    ├── pyspark_scripts/
│    │     ├── data_transformation.py
│    │     ├── data_validation.py
│    ├── sql_queries/
│    │     ├── create_tables.sql
│    │     ├── data_checks.sql
│    └── adf_arm_templates/
│          ├── pipeline_template.json
│          ├── linked_services.json


