# AWS Data Engineering Services: A Primer for Data Engineers

Amazon Web Services (AWS) offers a comprehensive suite of tools that are essential for building robust, scalable, and efficient data pipelines. If you looking to expand your cloud skills or transition to AWS-based data infrastructure, understanding these key services is crucial.

This table provides an overview of AWS services specifically relevant to data engineering workflows. If you're working with batch processing, real-time streaming, or complex data transformations, these services will help you.

What you get:
- Understand core AWS services for data pipeline development
- Identify the role of each service in the ETL/ELT process
- Recognize how different services integrate to create comprehensive data solutions


This reference is designed to be a practical roadmap for data engineers looking to leverage AWS's powerful data engineering ecosystem.


| Service | AWS Icon | Brief Utility | ETL Pipeline Stage |
|----------|---------|---------------|--------------------|
| **Data Sources** | 
| Amazon RDS | ![RDS Icon](icons/Arch_Amazon-RDS_48.png) | Managed relational database service | Extract (Source) |
| **Extract** |
| AWS Database Migration Service | ![DMS Icon](icons/Arch_AWS-Database-Migration-Service_48.png) | Migrate databases with minimal downtime | Extract |
| Amazon Kinesis Data Streams | ![Kinesis Icon](icons/Arch_Amazon-Kinesis-Data-Streams_48.png) | Real-time data streaming and ingestion | Extract |
| Amazon S3 | ![S3 Icon](icons/Arch_Amazon-Simple-Storage-Service_48.png) | Object storage for raw data files | Extract/Storage |
| **Transform** |
| AWS Glue | ![Glue Icon](icons/Arch_AWS-Glue_48.png) | ETL service for data preparation and transformation | Transform |
| AWS Glue Crawler | ![Glue Crawler Icon](icons/Res_AWS-Glue_Crawler_48.png) | Automatically discovers and catalogs data schemas | Transform (Metadata) |
| AWS Lambda | ![Lambda Icon](icons/Arch_AWS-Lambda_48.png) | Serverless compute for data transformation | Transform |
| Amazon Kinesis Data Firehose | ![Kinesis Firehose Icon](icons/Arch_Amazon-Data-Firehose_48.png) | Load streaming data to data stores | Transform/Load |
| **Load** |
| Amazon Redshift | ![Redshift Icon](icons/Arch_Amazon-Redshift_48.png) | Data warehousing and analytics | Load |
| Amazon Athena | ![Athena Icon](icons/Arch_Amazon-Athena_48.png) | Interactive query service for S3 data | Query/Load |
| **Orchestration & Management** |
| AWS Step Functions | ![Step Functions Icon](icons/Arch_AWS-Step-Functions_48.png) | Coordinate multiple AWS services | Workflow Management |
| Amazon EventBridge | ![EventBridge Icon](icons/Arch_Amazon-EventBridge_48.png) | Event-driven scheduling and routing | Orchestration |
| AWS Lake Formation | ![Lake Formation Icon](icons/Arch_AWS-Lake-Formation_48.png) | Create, secure, and manage data lakes | Data Governance |
| AWS Glue Data Catalog | ![Glue Catalog Icon](icons/Res_AWS-Glue_Data-Catalog_48.png) | Metadata repository for data assets | Metadata Management |
| **Visualization** |
| Amazon QuickSight | ![QuickSight Icon](icons/Arch_Amazon-QuickSight_48.png) | Business intelligence and visualization | Reporting |
| **Security & Governance** |
| AWS IAM | ![IAM Icon](icons/Arch_AWS-IAM-Identity-Center_48.png) | Identity and access management | Security |
