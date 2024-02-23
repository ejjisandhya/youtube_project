# Data Engineering YouTube Analysis Project 

**Project Overview**:
The objective of this project is to establish a secure and efficient framework for managing, streamlining, and analyzing structured and semi-structured data extracted from YouTube videos. The analysis will be centered around video categories and trending metrics.

**Project Goals**:
Data Ingestion: Develop a robust mechanism for ingesting data from diverse sources.

ETL System: Transform raw data into a standardized format conducive to analysis.

Data Lake: Implement a centralized repository (data lake) for storing data from multiple sources.

Scalability: Ensure the system can seamlessly scale to accommodate the growing volume of data.

Cloud Integration: Utilize AWS cloud services for processing large datasets efficiently.

Reporting: Construct a comprehensive dashboard to derive insights from the analyzed data.
_
Services Utilized

Amazon S3: Leverage Amazon S3 for object storage, providing scalability, data availability, security, and performance.

AWS IAM: Employ Identity and Access Management for secure management of access to AWS services and resources.

QuickSight: Utilize Amazon QuickSight, a scalable, serverless, machine learning-powered BI service for data visualization.

AWS Glue: Implement AWS Glue, a serverless data integration service facilitating data discovery, preparation, and aggregation for analytics and machine learning.

AWS Lambda: Leverage AWS Lambda, a serverless computing service enabling code execution without server management.

AWS Athena: Implement AWS Athena, an interactive query service for S3 that eliminates the need to load data, as it stays in S3.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

