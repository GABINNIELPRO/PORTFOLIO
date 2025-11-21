---
title: Data Warehouse for Project Management
publishDate: 2025-04-17 00:00:00
img: /assets/DATA.webp
img_alt: Data warehouse schema with ETL pipelines
description: |
  For the interior design firm in Bali, after centralizing project data through an ETL pipeline, the next step was to store it in a **PostgreSQL Data Warehouse**. The data was organized in **Bronze, Silver, and Gold layers** and structured with a **star schema**, enabling efficient querying, reporting, and decision-making.
tags:
 - Data Warehouse
 - ETL
 - Project Management
 - SQL
---

## 🏗️ Data Warehouse for Project Management

Following the ETL pipeline I developed for **Mary Kay Iteroir**, an interior design firm in **Bali**, the next step was to **store and structure all project data** efficiently in a Data Warehouse. This included **project elements, prices, invoices, and task tracking**, organized for fast access and analytics.

---

### 🧱 Data Pipeline Layers

To ensure clean and organized data, the warehouse was structured into **three layers**:

- 🟫 **Bronze layer**: Raw data from CSV files, Excel reports, and SQL databases  
- 🟪 **Silver layer**: Cleaned, normalized, and ready for analysis  
- 🟨 **Gold layer**: Aggregated and enriched data for dashboards and reports  

---

### ⭐ Star Schema

The Data Warehouse was built using a **star schema**:

- 📊 **Fact Table — Projects**  
  - project_id  
  - element_id  
  - invoice_id  
  - quantity  
  - total_cost  

- 🗂️ **Dimension Tables**:  
  - Elements  
  - Clients  
  - Suppliers  
  - Time  

---

### 📈 Analytics & Visualization

Thanks to the layered structure and star schema:

- ⚡ Queries were optimized using **indexes** for fast performance  
- 📉 Project managers could easily track **budgets, element usage, and invoices**  
- 📊 The warehouse powered **dashboards and summaries** for real-time project monitoring  

#### ⭐ Results

- 🗄️ **Centralization**: All project data stored in a single structured repository  
- ⚙️ **Efficiency**: Faster reporting, querying, and project tracking  
- 🔍 **Clarity**: Clear insights into project status, costs, and invoices  

---

### 🛠️ Technologies Used

- 🐘 **PostgreSQL** — Data Warehouse with star schema  
- 🧩 **SQL** — Table creation, indexing, queries  
- 🐍 **Python (pandas)** — Data cleaning & transformation  
- 🌬️ **Airflow** — ETL orchestration across Bronze/Silver/Gold layers  
- ⚛️ **React** — Frontend for project & element management  
