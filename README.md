# 🦠 Disease Detection Data Engineering Project

This project was built while learning **Data Engineering using Azure tools**.  
It demonstrates an end-to-end data pipeline for processing, transforming, storing, and visualizing disease-related data.

The goal is to simulate a real-world healthcare analytics pipeline using modern cloud data engineering tools.

---

## 🚀 Project Overview

This project focuses on:

- Data ingestion from raw sources
- Data transformation and cleaning
- Structured data storage in SQL
- Dashboard reporting using Power BI

It showcases how data engineering workflows are built in production environments.

---

## 🏗️ Architecture

Raw Data  
⬇  
Azure Data Factory (Data Ingestion & Pipeline Orchestration)  
⬇  
Azure Databricks (Data Transformation using PySpark)  
⬇  
Azure SQL Database (Structured Storage)  
⬇  
Power BI Dashboard (Visualization & Insights)

---

## 🛠️ Tech Stack

### Cloud & Data Engineering Tools
- Azure Data Factory (ADF)
- Azure Databricks
- Azure SQL Database
- Power BI

### Programming & Query Languages
- Python (PySpark)
- SQL

---

## 📂 Project Structure
disease-detection-project/
│
├── AzureDataFactory/        # ADF pipelines & data flow screenshots
│
├── databricks/              # Databricks transformation scripts
│   └── population_transformation.py
│
├── sql/                     # SQL table creation scripts
│
├── powerbi/                 # Power BI dashboard file (.pbix)
│
├── images/                  # Architecture & workflow screenshots
│
└── README.md