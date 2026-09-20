# End-to-End Medallion Architecture in Databricks

This project demonstrates an end-to-end **Medallion Architecture** in Databricks using real-world Olympic Games data.

The pipeline starts by ingesting raw Olympic data stored in **Azure Data Lake Storage (ADLS Gen2)** using Azure Data Factory.

The data then moves through the three layers of the Medallion Architecture:

- **Bronze Layer** – Stores the raw Olympic data with minimal transformation.
- **Silver Layer** – Cleans, transforms, and prepares the data for analysis using PySpark.
- **Gold Layer** – Creates business-ready tables designed for reporting and analytics.

Finally, the Gold layer is connected to Power BI to build interactive dashboards and visualize insights from the Olympic data.

The goal of this project is not only to understand what Bronze, Silver, and Gold mean, but to actually build and implement a complete Medallion Architecture from data ingestion to business intelligence.

## Technologies Used

**Azure Data Factory** | **Azure Data Lake Storage Gen2** | **Databricks** | **PySpark** | **Delta Lake** | **Power BI**
