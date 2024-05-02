# GCP-Data-Engineering-Project

Overview :

This project entails building a pipeline to facilitate the extraction of data pertaining to orders and order items from a relational database management system (RDBMS). The extracted data will then undergo processing to compute daily product revenue, followed by its integration into BigQuery tables. The primary objective is to make the processed data accessible to Business Analytics (BA) developers for the creation of requisite reports and dashboards.

![gcp project 1](https://github.com/aakriti-911/GCP-Data-Engineering-Project/assets/165250095/a1d70789-9857-43a4-b88b-09cf12f6925d)

Requirements :

Data Extraction: Retrieve relevant data from the RDBMS, specifically focusing on orders and order items.
Data Processing: Perform computation tasks to derive daily product revenue from the extracted data.
Data Loading: Incorporate the pre-processed daily product revenue data into designated BigQuery tables.
Accessibility: Ensure that BA developers have the necessary access and permissions to utilize the data stored in BigQuery for their reporting and dashboard development needs.

![gcp project 2](https://github.com/aakriti-911/GCP-Data-Engineering-Project/assets/165250095/f70a8c8c-c652-4b1d-b2dc-f7a9d89fe737)

Usage:

1. Data Extraction:
Utilize appropriate methods to query the RDBMS and extract the required data related to orders and order items.
2. Data Processing:
Implement computational logic to process the extracted data and compute daily product revenue.
3. Data Loading:
Establish a mechanism to load the pre-processed daily product revenue data into the designated BigQuery tables.
4. Report and Dashboard Development:
BA developers can leverage the data stored in BigQuery to generate the necessary reports and dashboards as per the project requirements.

We possess JSON files that are uploaded into Google Cloud Storage (GCS), serving as our data lake, containing data related to orders and order items. Our objective is to transform these JSON files into Parquet format. Subsequently, leveraging these Parquet files, we aim to perform computations to derive daily product revenue. To facilitate efficient data processing, we intend to create either views or tables. Following the computation of daily product revenue, the results are preserved in GCS in Parquet format.

We plan to utilize Spark code to read the data from Parquet files and load it into BigQuery for further analysis and utilization.

![gcp project 3](https://github.com/aakriti-911/GCP-Data-Engineering-Project/assets/165250095/8ae96022-4d58-4796-8cb0-a16f8145f13c)

Additional Considerations :

Ensure that error handling mechanisms are in place to address any issues encountered during the extraction, processing, or loading phases of the pipeline.
Implement appropriate logging functionalities to facilitate troubleshooting and monitoring of the pipeline activities.
We are automating the pipeline execution by scheduling it to run at regular intervals using tools like cron jobs or Apache Airflow.

Data Model :

![Data Model](https://github.com/aakriti-911/GCP-Data-Engineering-Project/assets/165250095/e0c06a5b-a49b-474d-8ae9-183acbf8c02c)



This overview outlines the project's objectives, requirements, and usage guidelines.


