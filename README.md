# YouTube Data Engineering & Analytics Pipeline

## Overview
This project focuses on securely managing, processing, and analyzing structured and semi-structured YouTube video data based on video categories and trending metrics.

## Project Goals
- 📥 **Data Ingestion** – Develop a pipeline to ingest data from multiple sources.
- 🔄 **ETL Processing** – Transform raw data into a structured format for analysis.
- 🏦 **Data Lake** – Store and manage data efficiently in a centralized repository.
- 📈 **Scalability** – Ensure the system scales as data volume increases.
- ☁️ **Cloud Integration** – Utilize AWS services for data processing and storage.
- 📊 **Reporting** – Build a dashboard to analyze key metrics and insights.

## Tech Stack & AWS Services Used
- **Amazon S3** – Object storage for raw and processed data.
- **AWS IAM** – Secure access management for AWS resources.
- **AWS Lambda** – Serverless compute for data transformation.
- **AWS Glue** – Serverless ETL service for data processing.
- **AWS Athena** – Interactive query service to analyze data stored in S3.
- **Amazon QuickSight** – Business intelligence tool for data visualization.
- **AWS CloudWatch** – Monitoring and alerting for system performance.

## Dataset Used
The dataset contains daily trending YouTube video statistics across multiple regions. It includes metadata such as video title, channel name, publish time, tags, views, likes, dislikes, descriptions, and comment counts. A `category_id` field is also provided in a JSON file.

**Dataset Source:**  
[YouTube Trending Videos Dataset - Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

**Architecture**

![youtube_analytics drawio](https://github.com/user-attachments/assets/dae0dcd3-6dd2-4a4b-b2e3-68fdadf04079)
