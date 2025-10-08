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
## Data Warehouse for Project Management

Following the ETL pipeline I developed for **Mary Kay Iteroir**, an interior design firm in **Bali**, the next step was to **store and structure all project data** efficiently in a Data Warehouse. This included **project elements, prices, invoices, and task tracking**, organized for fast access and analytics.

### Data Pipeline Layers

To ensure data quality and organization, the warehouse was structured into **three layers**:  
- **Bronze layer**: Raw data from CSV files, Excel reports, and SQL databases.  
- **Silver layer**: Cleaned and normalized data, ready for analysis.  
- **Gold layer**: Aggregated and enriched data for reporting and dashboards.

### Star Schema

The Data Warehouse was designed with a **star schema**:  
- **Fact Table**: Projects (project_id, element_id, invoice_id, quantity, total_cost)  
- **Dimensions**: Elements, Clients, Suppliers, Time  

### Analytics & Visualization

With the data structured in layers and the star schema:  
- Queries were optimized with **indexes** for fast retrieval.  
- Project managers could **track budgets, element usage, and invoices** easily.  
- The warehouse supported **dashboards and summaries** to monitor all ongoing projects efficiently.

#### Results

- **Centralization**: All project data stored in one structured repository.  
- **Efficiency**: Faster reporting and easier project tracking.  
- **Clarity**: Clear overview of project status, element costs, and invoices for better decision-making.  

---

### Technologies Used

- **PostgreSQL** : Data Warehouse storage with star schema.  
- **SQL** : Table creation, indexing, and queries.  
- **Python (pandas)** : ETL transformation and cleaning.  
- **Airflow** : ETL orchestration across Bronze, Silver, Gold layers.  
- **React** : Frontend interface for project and element management.  
