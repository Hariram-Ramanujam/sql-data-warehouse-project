# SQL Data Warehouse Project

## 🏗️ Data Architecture

This project follows the **Medallion Architecture**, consisting of three layers: Bronze, Silver, and Gold. Each layer represents a different stage of data processing, from raw data ingestion to business-ready analytical datasets.

### Medallion Architecture

| Layer | Description |
|---|---|
| **Bronze** | Stores raw data exactly as received from source systems. Data is ingested from ERP and CRM CSV files into SQL Server. |
| **Silver** | Performs data cleansing, standardization, validation, and transformation to ensure data quality and consistency. |
| **Gold** | Contains business-ready data modeled using a Star Schema, consisting of fact and dimension tables for reporting and analytics. |

## 📖 Project Overview

This project focuses on designing and implementing a modern data warehouse using SQL Server to consolidate sales data from multiple source systems.

The project covers the following activities:

1. **Data Architecture:** Design a modern data warehouse using the Bronze, Silver, and Gold layers.
2. **ETL Pipelines:** Build ETL processes to extract, transform, and load data from source CSV files into the warehouse.
3. **Data Modeling:** Develop fact and dimension tables using a Star Schema for analytical reporting.
4. **Data Analysis:** Write SQL queries to answer business questions and generate meaningful insights.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **SQL Server** | Database management and data warehouse implementation |
| **SQL Server Management Studio (SSMS)** | Database development and query execution |
| **Git & GitHub** | Version control and project documentation |
| **Draw.io** | Data architecture and data model visualization |
| **Notion** | Project planning, task tracking, and documentation |

### Important Links & Resources

- **SQL Server & SSMS:** Refer to the setup guide in the `00_setup` directory for installation instructions.
- **GitHub:** For version control and project sharing.
- **Draw.io:** For designing data architecture and data models.
- **Notion Template:** Project planning and task management.
- **Notion Project Steps:** Detailed guidance for each project phase.

## 🚀 Project Requirements

### 1. Data Warehouse Development (Data Engineering)

**Objective:**

Develop a modern data warehouse using SQL Server to consolidate sales data from ERP and CRM source systems, enabling analytical reporting and informed business decisions.

**Specifications:**

- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Identify, cleanse, and resolve data quality issues before loading data into the analytical layer.
- **Data Integration:** Integrate data from both source systems into a unified, user-friendly data model optimized for analytical queries.
- **Scope:** Focus exclusively on the latest available dataset. Historical data tracking and historization are not required.
- **Documentation:** Provide clear documentation of the data architecture, data model, and transformation processes to support business stakeholders and analytics teams.

### 2. BI: Analytics & Reporting (Data Analysis)

**Objective:**

Develop SQL-based analytics to generate actionable business insights and support strategic decision-making.

**Key Analysis Areas:**

- **Customer Behavior:** Analyze customer demographics, purchasing patterns, and customer activity.
- **Product Performance:** Evaluate product sales, product categories, and revenue contribution.
- **Sales Trends:** Identify sales patterns, monitor revenue, and analyze business performance over time.

These analyses will help stakeholders understand business performance and make data-driven decisions.

## 📂 Project Documentation

For detailed project specifications, requirements, and implementation steps, refer to:

- [`02_docs/requirements.md`](02_docs/requirements.md)

---

**Project Focus:** SQL Server | Data Engineering | Data Warehousing | ETL | Star Schema | SQL Analytics
