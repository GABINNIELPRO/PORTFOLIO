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

## 📁 ETL Pipeline & Project Management System

Mary Kay Iteroir, an interior design firm in **Bali**, faced the challenge of managing multiple projects simultaneously: tracking project elements (furniture, materials, décor), their prices, invoices, and progress. Data was scattered, and project monitoring was time-consuming and error-prone.

To solve this, I developed a **project management system** combined with an **ETL pipeline**, allowing the firm to centralize all project information and simplify daily operations.

---

### 📦 Data Sources

The system consolidated multiple types of data:  
- 🛋️ **Project elements**: furniture, materials, décor items  
- 💰 **Pricing information**: cost per element  
- 🧾 **Invoices**: client billing & supplier payments  
- 📅 **Project tracking**: tasks, deadlines, progress status  

---

### 🔄 ETL Pipeline

The ETL pipeline enabled structured and efficient data management:  
- 📥 **Extract**: Gathered data from spreadsheets, databases, and project tools  
- 🧹 **Transform**: Cleaned, normalized, and standardized all datasets  
- 📤 **Load**: Stored in **Amazon S3**, structured in **PostgreSQL** for easy querying  

---

### 📊 Analytics & Visualization

The system allowed the firm to:  
- 🔎 Track **project elements** and inventory  
- 💸 Monitor **prices and invoices**  
- 📋 Centralize **projects and tasks** for clearer progress tracking  
- 🖥️ Provide an **organized dashboard** for fast decision-making  

#### ⭐ Results

- 🗂️ **Organization**: All project data centralized and structured  
- ⚡ **Efficiency**: Faster management of elements, prices, invoices, and progress  
- 🔍 **Clarity**: Immediate access to essential project information  

---

### 🛠️ Technologies Used

- 🐍 **Python** – ETL core logic  
- 🐘 **PostgreSQL** – Structured project database  
- ☁️ **Amazon S3** – Centralized raw & processed data storage  
- 🌬️ **Airflow** – ETL workflow orchestration  
- ⚛️ **React** – Frontend for managing projects and elements  
