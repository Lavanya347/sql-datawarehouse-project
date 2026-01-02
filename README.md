# 📊 Data Warehouse and Analytics Project

## 📌 Project Summary

This project demonstrates the design and implementation of a **modern data warehouse** using **SQL Server**, following **Medallion Architecture (Bronze, Silver, Gold)**.
It showcases end-to-end **data engineering and analytics workflows**, from raw data ingestion to business-ready analytical insights.

- **Tech Stack:** SQL Server, T-SQL
- **Architecture:** Medallion (Bronze, Silver, Gold)
- **Data Sources:** ERP & CRM (CSV files)
- **Focus Areas:** ETL, Data Modeling, Data Quality, Analytics

---

## 🏗️ Data Architecture
<img width="1544" height="912" alt="data_architecture" src="https://github.com/user-attachments/assets/c8dd4560-b910-4259-b0e4-219505d3c9d6" />

The project follows the **Medallion Architecture** approach:

### 🔹 Bronze Layer

* Stores raw data ingested directly from source systems
* Data loaded from **ERP and CRM CSV files** into SQL Server
* No transformations applied

### 🔹 Silver Layer

* Data cleansing and standardization
* Handling missing values and data inconsistencies
* Normalized and structured data for downstream processing

### 🔹 Gold Layer

* Business-ready data modeled using a **Star Schema**
* Fact and Dimension tables optimized for analytical queries
* Designed to support reporting and decision-making

---

## 📖 Project Overview

This project covers the complete data lifecycle:

* **Data Architecture**
  Designing a scalable and maintainable data warehouse using Medallion Architecture

* **ETL Pipelines**
  Extracting, transforming, and loading data using T-SQL

* **Data Modeling**
  Creating fact and dimension tables for analytics and reporting

* **Analytics & Reporting**
  Writing SQL queries to generate actionable business insights

---

## 🔧 Skills Demonstrated

* Data Warehousing Concepts
* Medallion Architecture (Bronze, Silver, Gold)
* ETL Design & Implementation (T-SQL)
* Data Cleaning & Quality Validation
* Star Schema Data Modeling
* SQL-Based Analytics & Reporting

---

## 📊 Analytics Use Cases

The Gold layer enables analytical insights such as:

* Customer behavior analysis
* Product performance evaluation
* Sales trend analysis
* Key business metrics for decision-making

---

## 🚀 Project Requirements

### 🔹 Objective

Build a modern data warehouse using **SQL Server** to consolidate sales data and support analytical reporting.

### 🔹 Specifications

* **Data Sources:** ERP & CRM systems provided as CSV files
* **Data Quality:** Data cleansing and validation prior to analysis
* **Integration:** Unified analytical data model
* **Scope:** Latest dataset only (no historization)
* **Documentation:** Clear data model documentation for stakeholders

---

## 📂 Repository Structure

```
datasets/   → Source CSV files (ERP & CRM)
scripts/    → SQL scripts for ETL and data modeling
tests/      → Data quality and validation checks
docs/       → Data catalog and documentation
```

---

## ▶️ How to Run the Project

1. Load the CSV files into SQL Server
2. Execute Bronze layer ingestion scripts
3. Run Silver layer transformation scripts
4. Create Gold layer fact and dimension tables
5. Execute analytics queries for insights

---

## 🛡️ License

This project is licensed under the **MIT License**.

---

## 🌟 About Me

Hi, I’m **Lavanya** 👋
I’m an IT professional and aspiring **Data Analyst** passionate about building data-driven solutions.
I enjoy working with SQL, data warehousing, and analytics to transform raw data into meaningful insights.
This project is part of my portfolio to demonstrate hands-on experience in **data engineering and analytics**.

## 🔗 Connect with Me

📄 **[View My Resume](https://lavanya347.github.io/Assets/Lavanya_Data_Analyst_Resume.pdf)**  
🔗 **[LinkedIn Profile](https://www.linkedin.com/in/lavanya-lk)**  
📧 **Email:** lavanya347@gmail.com  
🧑‍💻 **[Portfolio](https://lavanya347.github.io/)**




