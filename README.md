# GCP-Data-Engineering-Project

Overview :

This project entails building a pipeline to facilitate the extraction of data pertaining to orders and order items from a relational database management system (RDBMS). The extracted data will then undergo processing to compute daily product revenue, followed by its integration into BigQuery tables. The primary objective is to make the processed data accessible to Business Analytics (BA) developers for the creation of requisite reports and dashboards.

![gcp project 1](https://github.com/aakriti-911/GCP-Data-Engineering-Project/assets/165250095/a1d70789-9857-43a4-b88b-09cf12f6925d)


![gcp project 2](https://github.com/aakriti-911/GCP-Data-Engineering-Project/assets/165250095/f70a8c8c-c652-4b1d-b2dc-f7a9d89fe737)


We possess JSON files that are uploaded into Google Cloud Storage (GCS), serving as our data lake, containing data related to orders and order items. Our objective is to transform these JSON files into Parquet format. Subsequently, leveraging these Parquet files, we aim to perform computations to derive daily product revenue. To facilitate efficient data processing, we intend to create either views or tables. Following the computation of daily product revenue, the results are preserved in GCS in Parquet format.

We plan to utilize Spark code to read the data from Parquet files and load it into BigQuery for further analysis and utilization.

![gcp project 3](https://github.com/aakriti-911/GCP-Data-Engineering-Project/assets/165250095/8ae96022-4d58-4796-8cb0-a16f8145f13c)
