# SQL Data Warehouse Project

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. 

---

## 📐 Data Architecture 
The data architecture for this project follows **Medallion Architecture** model, which organizes data intro three layers:

- **Bronze Layer**: Raw data ingestion from CSV files (ERP and CRM systems) without transformations.
- **Silver Layer**: Cleansed, standardized, and structured data prepared for analysis.
- **Gold Layer**: Business-ready data modeled in a star schema, optimized for reporting and analytics.

![Image](https://github.com/user-attachments/assets/783c7602-f46a-4121-aba8-da364fdd920a)

---

## 🚀 Poject Overview

This project includes:

  - **Data Architecture**: Designing a modern data warehouse using the Medallion approach.
  - **ETL Pipelines**: Extracting, transforming, and loading data from source CSVs.
  - **Data Modeling**: Building fact and dimension tables using the star schema for analytical use.
    
---

## 🎯 Project Objective

Build a modern SQL Server-based data warehouse to consolidate ERP and CRM sales data, enabling:

- Centralized analytics and reporting.
- Clean, integrated, query-optimized datasets.
- Business insights based on structured data models.

---

## 🛠️ Specifications

- **Data Sources**: CSV files from ERP and CRM systems.
- **Data Quality**: Data cleansing, deduplication, and validation.
- **Integration**: Merge both systems into a single star schema.
- **Scope**: Latest data only (no historical tracking).
- **Documentation**: Full metadata and model documentation for stakeholders and analysts.

---

## 📁 Repository Structure

```plaintext
sql-data-warehouse-project/
│
├── datasets/               # Raw ERP and CRM datasets (CSV format)
│
├── docs/                   # Architecture diagrams and metadata
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│
├── scripts/                # SQL scripts for all ETL stages
│   ├── bronze/             # Load raw data
│   ├── silver/             # Clean and transform data
│   ├── gold/               # Create star schema models
│
├── tests/                  # Data quality checks and validations
│
└── README.md               # Project documentation
```


