# data-analyst-yash
AWS Data Analytic Platform for the City of Vancouver
This repository showcases the development of a scalable and secure Data Analytic Platform (DAP) using AWS services to address urban challenges faced by the City of Vancouver. This project was undertaken as part of the BUSI 653: Cloud Computing Technologies course.

Project Overview
The DAP is divided into two phases:
Phase 1: Design and initial implementation, focusing on illegal dumping cases.
Phase 2: Expansion to analyze high water consumption concerns and graffiti incidents.

The platform leverages AWS tools for data ingestion, profiling, cleaning, analysis, and visualization to aid the City of Vancouver in data-driven decision-making.
Features

Scalability and Automation: A serverless architecture using AWS S3, Glue, and Athena.
Data Governance and Security: Comprehensive implementation of KMS encryption, S3 bucket versioning, and replication.
Real-Time Insights: CloudWatch dashboards for real-time monitoring and cost tracking.

Focused Analysis:
Illegal dumping case patterns.
High water consumption hotspots.
Graffiti incident resolutions.

Technologies Used
AWS S3 for scalable storage.
AWS Glue for data extraction, transformation, and loading.
AWS Athena for serverless querying.
AWS CloudWatch for monitoring and alerts.
DataBrew for data cleaning and profiling.

Project Workflow
Data Collection and Storage:

Raw datasets are ingested into S3 buckets.
Subfolders are structured for profiling, cleaning, and unsaved work.
Data Cleaning and Transformation:

Handled using AWS Glue DataBrew.
Data schema validation, missing value handling, and irrelevant column removal.
Query and Analysis:

AWS Athena is used for SQL-based data exploration.
Analysis focused on specific use cases like illegal dumping and high water consumption.
Visualization:
Insights displayed on CloudWatch dashboards with widgets for key metrics like bucket size, API calls, and estimated costs.
![Sample Dashboard](images/dashboard-sample.png)


