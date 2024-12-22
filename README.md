# ETL Pipeline with Data Fusion, Airflow, and BigQuery


This repository includes the code and configuration files for an Extract, Transform, Load (ETL) project utilizing Google Cloud Data Fusion for data extraction, Apache Airflow/Cloud Composer for orchestration, and Google BigQuery for data loading. The project is designed to automate the end-to-end data pipeline, ensuring efficient and secure data handling from extraction to transformation and ultimately to loading into BigQuery for analysis.

## Overview

**Data Extraction** 
The project will leverage Python to efficiently extract data from multiple source systems, ensuring that all necessary information is gathered for further processing.

**Data Masking and Transformation**
To safeguard sensitive data, Cloud Data Fusion will be used to apply masking and encoding techniques. This step ensures that only anonymized or transformed data is transferred to BigQuery, complying with privacy and security standards.

**Data Loading into BigQuery**
Transformed data will be loaded into Google BigQuery, where it will be stored in structured tables, ready for analysis, reporting, and further processing.

**Pipeline Orchestration with Airflow**
The entire ETL workflow will be automated using Apache Airflow, orchestrated via Cloud Composer. This ensures that the extraction, transformation, and loading processes run reliably, efficiently, and on schedule.

**Data Visualization with Looker**
Looker will be integrated into the pipeline to provide advanced data visualization and reporting capabilities. This allows stakeholders to derive insights from the data loaded into BigQuery, enabling informed decision-making through dynamic and interactive dashboards.
