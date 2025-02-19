# DE-Youtube-Analysis

## Overview

This project focuses on securely managing, streamlining, and analyzing structured and semi-structured YouTube video data. The analysis is centered around video categories and trending metrics.

## Project Goals
1. Data Ingestion: Develop a mechanism to ingest data from various sources.
2. ETL System: Transform raw data into a structured format suitable for analysis.
3. Data Lake: Establish a centralized repository for data collected from multiple sources.
4. Scalability: Ensure that the system scales seamlessly as data volume grows.
5. Cloud Integration: Leverage AWS for processing vast amounts of data beyond local computing capabilities.
6. Reporting: Create a dashboard to provide insights and answer key questions.

## Services we will be using
1. Amazon S3: Object storage service offering scalability, data availability, security, and performance.
2. AWS IAM: Identity and Access Management to securely control access to AWS resources.
3. Amazon QuickSight: Scalable, serverless business intelligence service with embedded machine learning capabilities.
4. AWS Glue: Serverless data integration service to discover, prepare, and combine data for analytics and machine learning.
5. AWS Lambda: Compute service for running code without managing servers.
6. AWS Athena: Interactive query service for data stored in S3, eliminating the need to load data elsewhere.

## Dataset Used
The project uses a Kaggle dataset containing daily statistics on popular YouTube videos over several months. Key features include:
Up to 200 trending videos per day across multiple regions.
Information such as video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count.
A category_id field is linked via a JSON file for each region.
For more details, check out the dataset on Kaggle.

https://www.kaggle.com/datasets/datasnaek/youtube-new



