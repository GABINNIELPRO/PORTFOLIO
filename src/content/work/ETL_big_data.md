---
title: ETL Pipeline & Project Management System
publishDate: 2025-04-17 00:00:00
img: /assets/ETL.webp
img_alt: Project management and ETL system
description: |
  For an interior design firm based in Bali, managing project elements, prices, invoices, and task tracking was becoming increasingly complex. This project involved designing a **project management system** with an ETL pipeline to centralize and organize all project-related data efficiently.
tags:
 - ETL
 - Project Management
 - Data Engineering
---
## ETL Pipeline & Project Management System

Mary Kay Iteroir, an interior design firm in **Bali**, faced the challenge of managing multiple projects simultaneously: keeping track of project elements (furniture, materials, décor), their prices, invoices, and overall progress. Data was scattered, and project tracking was time-consuming and error-prone.  

To solve this, I developed a **project management system** combined with an **ETL pipeline**, allowing the firm to centralize all project information and simplify daily operations.

### Data Sources

The system consolidated multiple types of data:  
- **Project elements**: furniture, materials, décor items.  
- **Pricing information**: costs of each element.  
- **Invoices**: records of client billing and supplier payments.  
- **Project tracking**: task status, deadlines, and progress updates.  

### ETL Pipeline

The ETL pipeline enabled structured and efficient data management:  
- **Extract**: Collected data from spreadsheets, databases, and project management tools.  
- **Transform**: Cleaned, normalized, and organized data for consistency.  
- **Load**: Stored in **S3** and structured in a **PostgreSQL database** for easy access and retrieval.

### Analytics & Visualization

The system allowed the firm to:  
- Track **project elements** and manage inventory.  
- Monitor **prices and invoices** for each element.  
- Centralize **projects and task tracking** for a clear overview of progress.  
- Provide a **structured and easily accessible dashboard** for efficient project management.

#### Results

- **Organization**: All project-related data centralized and structured.  
- **Efficiency**: Easier management of elements, pricing, invoices, and project progress.  
- **Clarity**: Quick access to essential project information for planning and decision-making.  

---

### Technologies Used

- **Python** : Core logic and ETL implementation.  
- **PostgreSQL** : Structured database for project data.  
- **S3** : Data storage for centralizing all project information.  
- **Airflow** : ETL workflow orchestration.  
- **React** : Frontend interface for managing projects and tracking elements.  
