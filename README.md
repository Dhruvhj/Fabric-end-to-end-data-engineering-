# Fabric-end-to-end-data-engineering-

<img width="765" height="215" alt="Project Architecture" src="https://github.com/user-attachments/assets/4ffe0569-3a6f-4ca9-bf61-de0e0c6e5b77" />

This repository contains a complete end-to-end data engineering pipeline built using Microsoft Fabric Lakehouse, demonstrating real-world ETL, data modelling, and analytics workflows.

This project showcases my ability to build scalable and production-style data systems using modern tools across ingestion, transformation, orchestration, and reporting.

🚀 Project Overview

This project processes raw sales data and transforms it into a clean Dimensional Model (Fact + Dimension tables) using:

Microsoft Fabric Lakehouse

Fabric Notebooks (PySpark)

Fabric Data Pipelines

SQL for DWH Modelling

Lakehouse Staging → Silver → Gold layers

🧱 Project Architecture

Flow:

Raw CSV → Staging Layer → Transformations → Fact Table → Dimension Tables → Analytics-Ready Layer

(Optional: I can generate an architecture diagram for you.)

📂 Repository Structure
data/                     → Raw sales dataset  
sql/                      → SQL scripts for schema + data load  
notebooks/                → Fabric notebook (ETL & transformations)  
pipeline/                 → Screenshots / JSON of the Fabric pipeline  
architecture/             → System design diagrams  
📌 Files Included
📁 data/

sales.csv — Raw sales dataset used for ingestion

📁 sql/

SchemaFact&DimTablesQueryFabricDWH.sql
Contains Fact + Dimension table creation queries

LoadDataFromStagingLakehouseinFact&DimTables.sql
Inserts data into Fact & Dim tables from Staging

📁 notebooks/

PySpark notebook for Fabric transformations (optional to upload)

🎯 Key Features of This Project

✔ Built entirely using Microsoft Fabric Lakehouse
✔ Created staging & model schemas following DWH best practices
✔ Loaded raw data → cleaned → modelled into Fact/Dim
✔ Fabric pipeline executes all steps end-to-end
✔ SQL-based star schema for reporting
✔ Ready for BI tools (Power BI / Fabric Warehouse)

🛠️ Tools & Technologies Used

Microsoft Fabric Lakehouse

PySpark Notebooks

Fabric Data Pipelines

SQL (T-SQL)

Delta Tables

Data Modelling (Star Schema)

📈 Results

This project demonstrates:

Data ingestion automation

Data modelling using Fact & Dimension tables

Production-style Fabric pipeline

Real-world data engineering workflow
