---
title: Data Warehouse for Business Analytics
publishDate: 2025-04-17 00:00:00
img: /assets/DATA.webp
img_alt: Data warehouse schema with ETL pipelines
description: |
  This project focuses on the design and implementation of a Data Warehouse to centralize and analyze heterogeneous business data. It includes ETL processes, database modeling, and dashboard creation for decision-making.
tags:
 - Data Warehouse
 - ETL
 - Business Intelligence
 - SQL
---

## Data Warehouse for Business Analytics

> "Without data, you're just another person with an opinion." — W. Edwards Deming

In this project, we designed and implemented a **Data Warehouse** to help an organization centralize, clean, and analyze its data for better decision-making.

### Data Sources

We integrated heterogeneous datasets such as:
- **CSV files** (sales, products, customers)
- **Excel reports** (monthly KPIs)
- **Relational databases** (PostgreSQL, MySQL)

### ETL/ELT Pipeline

A complete **ETL pipeline** was developed:
- **Extract**: Retrieve raw data from Excel, CSV, and SQL databases.
- **Transform**: Data cleaning, normalization, and aggregation using **Python (pandas)** and **SQL scripts**.
- **Load**: Centralization into a **PostgreSQL Data Warehouse** with a **star schema** (fact and dimension tables).

#### Schema Example
- **Fact Table**: Sales (date, product_id, customer_id, revenue, quantity)
- **Dimensions**: Time, Products, Customers, Regions

### Analytics & Visualization

Once the data warehouse was built:
- Queries were optimized using **SQL indexing and partitioning**.
- Dashboards were created in **Power BI / Tableau** to visualize KPIs (sales trends, customer segmentation, product performance).

#### Results

- Improved **reporting speed** by centralizing data.
- Enabled **ad-hoc queries** by business users.
- Clear visualization of sales performance and customer behavior.

---

### Technologies utilisées

- **PostgreSQL** : Base de données pour le Data Warehouse.
- **SQL** : Création des tables, index, vues analytiques.
- **Python (pandas)** : Prétraitement et transformation des données.
- **Airflow** (basics) : Orchestration des workflows ETL.
- **Power BI / Tableau** : Création de dashboards interactifs.
