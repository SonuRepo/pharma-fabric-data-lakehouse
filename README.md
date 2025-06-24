<<<<<<< HEAD

# Pharma Manufacturing Data Lakehouse Project

This project showcases end-to-end capabilities including ingestion from multiple file formats, 
Bronze-Silver-Gold architecture, star schema modeling, and Power BI-style visualizations using Python.

---

# Key Highlights

Multi-format data ingestion (CSV, Excel, JSON) via Fabric Pipelines & Dataflow Gen2

Bronze --> Silver --> Gold architecture for data processing

# Star Schema model:

Fact Tables: fact_sales, fact_production, fact_qc
Dimension Tables: dim_product, dim_supplier, dim_region, dim_machine
Data quality, standardization, type casting, and enrichment done in Silver Layer.
Advanced analytics using Seaborn, Plotly, and Pandas inside Fabric Notebooks.

# Business Use Cases Covered

Monthly sales trends by region
Top-performing products by revenue
Downtime distribution for production efficiency
QC pass/fail result distribution
Machine health monitoring (Temperature vs RPM)
Inventory stock reporting

# Tools & Technologies

Microsoft Fabric (Lakehouse, Dataflow Gen2, Pipelines, Notebooks)
PySpark, Pandas, Seaborn, Plotly
OneLake storage & delta tables
No Power BI required - entire solution built with notebooks



##  Project Overview

| Feature                          | Description |
|----------------------------------|-------------|
| **Domain**                       | Pharmaceutical Manufacturing |
| **Platform**                     | Microsoft Fabric (Free Trial) |
| **Data Sources**                 | Excel, CSV, JSON |
| **Tech Stack**                   | Dataflow Gen2, Fabric Pipelines, Lakehouse, PySpark Notebooks, Seaborn, Plotly |
| **Layers**                       | Bronze --> Silver --> Gold |
| **Modeling**                     | Star Schema (Fact & Dimension) |
| **Visualizations**               | Embedded in Notebooks |

---


## Features Implemented

-  Multi-source ingestion using Pipelines and Dataflow Gen2
-  File formats: CSV, Excel, JSON (non-clinical pharma data)
-  Bronze Layer: Raw loading
-  Silver Layer: Cleansing, joining, standardization
-  Gold Layer: Star schema modeling (fact & dimension)
-  Professional-grade analytics using Seaborn/Plotly

---

## Sample Visuals

Visuals are generated in the notebook using `matplotlib`, `seaborn`, and `plotly`.

| Visualization                    | Description |
|----------------------------------|-------------|
|  Monthly Sales by Region         | Revenue trend by month |
|  Top 10 Products by Revenue      | Product performance |
|  Downtime Boxplot                | Batch efficiency |
|  QC Test Result Distribution     |  Quality analysis |
|  Temperature vs RPM Scatter      | Sensor trends |

Monthly Sales by Region 
![Monthly Sales by Region ](<Monthlu revenue by sales.png>)
![Monthly Sales by Region Graph](<Monthly revenue by sales graph.png>)

All others graph are present in notebook kindly check visualization notebook

---

## Learning Outcomes

- Handling real-world file formats and ingestion mechanisms
- Implementing medallion architecture in Microsoft Fabric
- Building analytical models using star schema design
- Producing rich visualizations without Power BI
- Realizing an end-to-end data lakehouse solution for a manufacturing use case

---

##Author

**Sonu Kumar**  
Data Engineer (Azure | Fabric | PySpark)  
Email: your.email@example.com  
LinkedIn: [https://www.linkedin.com/in/sonu-kumar-13550118b/]
---
=======
# pharma-fabric-data-lakehouse
Full-scale Fabric project with star schema &amp; visualizations
