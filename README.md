# Zillow Rapid API Data Pipeline Project

This project is an end-to-end data pipeline hosted on an AWS EC2 Instance that uses Airflow DAGS to pull proxy Zillow real estate data from Rapid API.

Once pulled from Rapid API, the proxy Zillow data is pulled and transformed through a series of AWS S3 buckets before ultimately being stored and visualized in AWS Redshift and AWS Quicksight, respectively.

Project composed with aid from the tutorial ["Zillow Data Analytics (RapidAPI) | End-To-End Python ETL Pipeline | Data Engineering Project"](https://www.youtube.com/watch?v=j_skupZ3zw0) by Yemi Olani.


### Airflow DAGS Graph

![zillow_airflow_img](airflow/zillow_airflow_img.png)


### AWS S3 Bucket with Rapid API Data

![zillow_s3_img](aws/zillow_s3_img.png)


### AWS Redshift Table Creation

![zillow_redshift_img](aws/zillow_redshift_img.png)


### AWS QuickSight Visualization

![zillow_quicksight_img](aws/zillow_quicksight_img.png)
