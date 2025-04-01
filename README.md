# YouTube Data Analytics ETL Pipeline on AWS

## Overview
This project aims to securely manage, streamline, and perform analysis on structured and semi-structured YouTube video data based on video categories and trending metrics.

## Project Goals
- **Data Ingestion** — Build a mechanism to ingest data from different sources.
- **ETL System** — Transform raw data into a format suitable for analysis.
- **Data Lake** — Centralized repository to store data from multiple sources.
- **Scalability** — Ensure the system scales with increasing data.
- **Cloud** — Utilize AWS for cloud-based processing of large datasets.
- **Reporting** — Create a dashboard for querying and visualizing the analysis.

## Services we will be using
- **Amazon S3**: An object storage service providing scalability, data availability, security, and performance.
- **AWS IAM**: Identity and access management to securely manage access to AWS services and resources.
- **QuickSight**: A scalable, serverless, machine learning-powered business intelligence service built for the cloud.
- **AWS Glue**: A serverless data integration service for discovering, preparing, and combining data for analytics and machine learning.
- **AWS Lambda**: A computing service for running code without provisioning or managing servers.
- **AWS Athena**: An interactive query service for S3 that allows running SQL queries directly on data in S3 without loading it.

## Dataset Used
The dataset used is from Kaggle, containing statistics (CSV files) on daily popular YouTube videos over many months. There are up to 200 trending videos published daily across various locations. Each region's data is in its own file, containing video title, channel title, publication time, tags, views, likes and dislikes, description, comment count, and a category ID specific to the region.

Dataset link: [Kaggle YouTube Data](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## Architecture Diagram
![architecture](https://github.com/user-attachments/assets/65a00b14-1ed3-494b-b1e6-22e1728d4d0d)
