# NYC_TAXI_DATA_ENGINEERING_PROJECT

1. Project Structure:
This screenshot shows the overall organization of the NYC Taxi Data Engineering project, including the Azure Data Factory configuration, Databricks notebooks, Bronze and Silver data layers, Gold-layer outputs, and Power BI artifacts.

<img width="1536" height="1024" alt="project_structure_nyc_taxi" src="https://github.com/user-attachments/assets/4303b271-fd75-41ea-9d9f-28313f73fa4d" />

                      
2. Azure Resource Group:
This screenshot shows the Azure Resource Group containing the core resources used in the project, providing a centralized view of the services required for the end-to-end data engineering workflow.

<img width="952" height="470" alt="ResourceGroup_P1" src="https://github.com/user-attachments/assets/3ee07fd1-47c1-4613-b210-d67e7f580290" />

3. Azure Data Factory:
Azure Data Factory Pipeline -
This screenshot shows the Azure Data Factory pipeline used to ingest NYC Taxi data from the source into Azure Data Lake Storage Gen2. The pipeline is parameterized to support dynamic file ingestion and reusable data-loading workflows.

<img width="959" height="470" alt="ADF_p1" src="https://github.com/user-attachments/assets/cd6ed986-a905-490a-b433-c080f556fc7a" />

4. Azure Databricks:
Azure Databricks – Data Transformation -
This screenshot shows the Databricks environment used for PySpark-based data processing and transformation. The data is processed through the Bronze, Silver, and Gold layers following the Medallion Architecture.

<img width="958" height="476" alt="Databricks_p1" src="https://github.com/user-attachments/assets/3a59b337-6b87-4ad4-a936-c4f2b92768c9" />

5. Power BI:
Power BI Dashboard -
This screenshot shows the Power BI dashboard built on the transformed Gold-layer data. It provides interactive visualizations and business insights such as trip analysis, zone-wise performance, and revenue/trend analysis.

<img width="955" height="524" alt="PowerBI_p1" src="https://github.com/user-attachments/assets/f345241c-f548-4afc-8d06-07f27fb73f2f" />
