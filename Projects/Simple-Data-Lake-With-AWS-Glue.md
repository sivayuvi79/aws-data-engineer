## Project Objective

This project demonstrates how to build a modern data analytics platform for a music streaming company (DeFtunes) using AWS services and best practices. The solution leverages a medallion architecture to enable scalable, reliable, and insightful analytics.

### What You'll Accomplish

1. **Data Ingestion & Transformation**: Extract purchase and streaming data from APIs and operational databases, then transform and enrich it using AWS Glue ETL.
2. **Data Lake Storage**: Store raw and processed data in Amazon S3, organizing it into landing, silver (Iceberg tables), and gold (Redshift) zones.
3. **Metadata Management**: Use AWS Glue crawlers to catalog data and manage metadata for discoverability and governance.
4. **Data Modeling**: Model the data into a star schema using dbt, optimizing it for analytics and reporting.
5. **Data Querying**: Query data efficiently using Amazon Athena and Amazon Redshift.
6. **Infrastructure as Code**: Implement the entire pipeline and supporting infrastructure using Terraform for reproducibility and scalability.

### Optional Exploration
Explore the impact of **compression** and **partitioning** on storage costs and query performance in Amazon S3 and Redshift.

By the end of this project, you'll gain hands-on experience with AWS Glue, Amazon S3, Apache Iceberg, Amazon Redshift, dbt, and Terraform—empowering you to build and optimize enterprise-grade data platforms on AWS.