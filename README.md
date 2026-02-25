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



## 📂 Project Structure
```
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
```
## 🔄 Data Pipeline Workflow

### 1️⃣ Data Ingestion
- Azure Data Factory loads raw disease data from source
- Data is transferred to Azure Data Lake / staging layer

### 2️⃣ Data Transformation
- Databricks performs:
  - Data cleaning
  - Null handling
  - Standardization
  - Aggregation

### 3️⃣ Data Storage
- Cleaned data is stored in Azure SQL tables
- Tables optimized for reporting queries

### 4️⃣ Reporting & Visualization
- Power BI connects to Azure SQL
- Interactive dashboard created for:
  - Disease trends
  - Region-wise analysis
  - Population impact
  - Statistical insights

---

## 📊 Dashboard Features

- Trend analysis
- Region-wise comparison
- Filter by date
- KPI metrics
- Interactive visuals

---

## 📸 Screenshots

### Azure Data Factory Pipeline
![ADF Pipeline](images/adf_dataflow.png)

### SQL Tables
![SQL Tables](images/sql_tables.png)

### 🔷 Power BI Dashboard
![Power BI Dashboard](images/Powerbi_image.png)

### Power BI Dashboard
(Preview available inside `powerbi/covid19_reporting.pbix`)

---

## 🎯 Key Learnings

- Building end-to-end data pipelines
- Working with distributed processing in Databricks
- SQL optimization for reporting
- Data modeling for BI dashboards
- Orchestrating workflows using ADF

---

## 📌 Future Improvements

- Add incremental data loading
- Implement Delta Lake
- Add automated CI/CD deployment
- Integrate real-time streaming data

---

## 👨‍💻 Author

**Aryash Badjatya**  
B.Tech Computer Science  
Aspiring AI Engineer | Data Engineering | Machine Learning

---

⭐ If you found this project useful, consider giving it a star!