# SQL Data Warehouse Project

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. 

---

## Data Architecture 
The data architecture for this project follows *Medallion** Architecture **Bronze**, **Silver**, and **Gold** layers:
![Image](https://github.com/user-attachments/assets/783c7602-f46a-4121-aba8-da364fdd920a)

1. **Bronze Layer:** Raw data is imported directly from CSV files into the SQL Server database without any transformation
2. **Silver Layer:** This layer cleans, standardizes, and organizes the data to make it ready for analysis.
3. **Gold Layer:** This layer stores business-ready data structured in a star schema for reporting and analytics.

---
## Poject Overview
This project includes:
  1. **Data Architecture:** Building a modern data warehouse using the Medallion Architecture **Bronze**, **Silver** and **Gold** layers.
  2. **ETL Pipelines:** Extracting, transforming and loading data from source systems into the warehouse.
  3. **Data Modeling:** Creating fact and dimension tables designed for analytical queries.

---

## Project Requirements
### Building the Data Warehouse 
#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

## Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
```


