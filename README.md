# GHG and Methane Emissions Monitoring and Analysis Using AWS Glue and AWS QuickSight

# Project Overview
This project aims to establish a scalable and automated system for monitoring GHG and Methane emissions using AWS services. By leveraging Amazon S3 for data storage, AWS Glue for ETL processing, Athena for querying, and QuickSight for visualization, this system enables real-time and historical analysis of emissions data to support environmental research and policy-making.

# Key Features
1. Automated Data Ingestion: Collects emissions data from various sources into Amazon S3.
2. ETL Processing with AWS Glue: Cleans, transforms, and enriches raw data for structured analysis.
3. Efficient Querying with Athena: Enables fast, SQL-based querying of both raw and processed data.
4. Interactive Dashboards with QuickSight: Provides insights through dynamic visualizations and heatmaps.
5. Performance Monitoring: Uses CloudWatch to track system performance and ensure reliability.

# Tech Stack
- Cloud Services: AWS Glue, Amazon S3, AWS Athena, Amazon QuickSight, AWS CloudWatch
- Data Processing: PySpark, AWS Glue Data Catalog
- Visualization: Amazon QuickSight dashboards

# Dataset
The dataset includes global GHG and Methane emissions data from 1850 to 2022, sourced from Our World in Data. Key fields include:
- Entity (Country)
- Code
- Year
- GHG Emissions
- Methane Emissions

# Project Workflow
1. Data Ingestion: Store raw emissions data in an S3 bucket.
2. Data Transformation: Use AWS Glue to clean and preprocess data.
3. Data Storage: Save transformed data in Amazon S3.
4. Batch Processing: Run scheduled AWS Glue jobs for historical trend analysis.
5. Data Analysis: Query structured data using Athena.
6. Visualization: Use QuickSight dashboards for insights on emissions trends.

# AWS QuickSight Dashboards
- Global GHG and Methane Trends (Line Charts)
- Country-wise Emissions Over 200 Years (Bar Charts)
- GHG & Methane Emissions Heatmaps (Geospatial Visualization)

# Results & Insights
- Identified top contributors to emissions over time.
- Analyzed historical trends and regional variations in emissions.
- Provided a visual representation for policymakers and researchers to track climate impact.

# How to Run the Project
1. Set up AWS IAM roles for Glue and S3 access.
2. Upload the dataset to an S3 bucket (ghg-methane/raw_data).
3. Configure AWS Glue crawlers and ETL jobs to process data.
4. Use Athena to query transformed data.
5. Create interactive dashboards in Amazon QuickSight.

# Conclusion
This project provides a scalable, cloud-based solution for emissions monitoring, offering actionable insights for climate research and decision-making.

# References
- Our World in Data - CO2 & Greenhouse Gas Emissions
- NOAA Real-time Data
- OpenWeatherMap API
