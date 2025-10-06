# Data-Driven Healthcare: Transforming Metro-City Hospital with Microsoft Fabric
# Project Overview:
This project showcases the design and implementation of a cloud-based data engineering solution for Metro-City Hospital using Microsoft Fabric and Azure Data Factory (ADF).
The solution follows a Medallion Architecture (Bronze–Silver–Gold) approach to enable efficient ingestion, transformation, and analysis of large-scale healthcare data.
By modernizing data workflows, the project empowers the hospital to gain actionable insights, improve patient outcomes, and support data-driven decision-making.

# Project Goals:
1. Ingest medical data from multiple sources into the cloud-based data platform.

2. Clean and preprocess the raw data to ensure accuracy, consistency, and completeness.

3. Transform data into structured formats suitable for analytics and reporting.

4. Load data into a data warehouse using a scalable and efficient architecture.

5. Ensure data quality, performance, and scalability throughout the pipeline.

6. Enable analysts and researchers to query, explore, and visualize the data seamlessly within Microsoft Fabric.


# Technologies & Tools Used:

1. Cloud Platform: Microsoft Fabric, Microsoft Azure

2. Data Integration & Orchestration: Azure Data Factory (ADF)

3. Data Storage: OneLake / Lakehouse architecture (Bronze, Silver, Gold layers)

4. Data Processing & Transformation: PySpark Notebooks, Dataflows Gen2

5. Data Modeling: Dimensional (OLAP) Data Model, Star Schema

6. Data Warehouse: Fabric Data Warehouse (EDW)

7. Visualization & Analytics: Power BI

8. Version Control & Collaboration: GitHub

9. Scheduling & Automation: ADF Pipelines (daily refresh schedule)

# Project walkthrough 
This walkthrough documents each stage of the project, including screenshots and brief descriptions.

# Data model design for Metro-City Hospital
![1002992490](https://github.com/user-attachments/assets/ee21a12b-2d8c-442c-a87a-27cc8f0c8d32)


# Loading hospital data into Bronze layer via Azure Data Factory (ADF)
Automated the ingestion of raw hospital data into the Bronze layer using Azure Data Factory, laying the foundation for scalable data processing and analytics.
<img width="1366" height="615" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/938b74d0-be79-4629-996d-6077718fcfcd" />


# Add Silver Notebook activity for data transformation
Implemented Silver layer transformations using Fabric Notebooks to clean, enrich, and structure raw hospital data for downstream analytics and reporting.
<img width="1366" height="521" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/eb7cc40a-ca58-4bfb-97b6-85c14dcef41e" />


# Add Gold Notebook activity for data storage
The Gold layer would store processed patient, imaging, lab, and medical records data ready for research, disease prediction, and operational insights.
<img width="1366" height="504" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/2f9e007f-65af-4488-9426-3d1a901b554a" />


# Process workspace
A dedicated environment for exploring, validating, and transforming raw data. Enables safe testing of data pipelines, debugging, and experimentation.
<img width="1366" height="543" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/b12118ab-cf69-4378-86a5-32b2aefb4c2f" />


# Recommendations

# Data Quality Improvements

1. Standardize input formats using schema enforcement to ensure consistency.

2. Validate records to automatically detect and handle missing or incomplete data.

3. Automate error handling with logging and correction workflows in ETL pipelines.

# Operational Enhancements

1. Train staff on accurate data entry to minimize downstream errors.

2. Monitor pipelines in real-time with dashboards tracking performance, data freshness, and anomalies.

3. Optimize pipelines continuously, leveraging incremental loads, resource scaling, and performance tuning for efficiency and scalability.

