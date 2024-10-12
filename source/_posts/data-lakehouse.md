---
title: AWS Data Lakehouse
cover: https://res.cloudinary.com/dscnnrudb/image/upload/w_200,h_200/v1722670519/portfolio/postimages/datalakehouse/lakehousecover_wppffa.jpg
date: 2098-1-1 00:00:00
---

## Description
A scalable data architecture that enhances dashboard KPI visualizations, promotes secure storage in AWS S3, and fosters collaboration among key stakeholders.
The Data Lakehouse Architecture combines the strengths of traditional data warehouses and data lakes. It comprises various AWS services, including Athena, Glue, and S3, with three primary data buckets: Bronze (raw data), Silver (lightly transformed data), and Gold (business-ready data). The dashboard application is built using Streamlit and Django, with a focus on role-based access control.
## Tech Stack
- **Oracle NetSuite**: a leading cloud ERP solution. Data extraction from Oracle NetSuite utilizes the NetSuite Saved Search API, which offers some data cleaning capabilities, though they may not be entirely effective.
- **AWS Glue Crawler**: Data can also be sourced from various other databases using AWS Glue Crawlers to discover and catalogue metadata from various sources, including native clients (Amazon Simple, S3, Apache Iceberg .etc), JDBC (MYSQL, Microsoft SQL .etc) and MongoDB clients.
- **AWS Glue Job**: This service offers ETL capabilities to extract data from various sources, transform it at each stage, and load it to the subsequent bucket or destination.
- **AWS S3**:\
Bronze Bucket: Acts as the raw data landing zone. Data is ingested without any transformation.\
Silver Bucket: Data from the Bronze bucket undergoes light transformations before being stored here.\
Gold Bucket: Contains the final, business-ready data.
- **AWS Athena**:An interactive query service by AWS that allows data analysis directly in Amazon S3 using standard SQL.
- **Streamlit**: An open-source Python framework for data scientists and AI/ML engineers to deliver dynamic data apps.

## Features
#### Comprehensive Data Processing Pipeline
This pipeline offers seamless data retrieval from multiple data sources, simplifying data collection and integration.
#### Durable And Secure Storage
With industry-leading security measures, S3 ensures that data is protected while offering virtually unlimited scalability. This highly secure storage solution is available at a cost-effective price, ensuring both high performance and low operational costs.
#### Affordable and Fast Data Query
The solution integrates AWS Athena for data querying, allowing for cost-effective, serverless queries directly on S3-stored datasets. Athena delivers rapid insights without the need to manage any infrastructure, making it an ideal tool for ad-hoc queries and analytics.

## Demos
<table style="width:100%">
    <colgroup>
       <col span="1" style="width: 50%;">
       <col span="1" style="width: 50%;">
    </colgroup>
    <tr>
        <td>
            AWS Data Lakehouse Architecture/Workflow
            <img src="https://res.cloudinary.com/dscnnrudb/image/upload/v1722670519/portfolio/postimages/datalakehouse/awsworkflow_yjxzcm.jpg"/>
        </td>
        <td>
            Front End Architecture (Refined)
            <img src="https://res.cloudinary.com/dscnnrudb/image/upload/v1728233417/portfolio/postimages/datalakehouse/Dashboard_Layered_Architecture_k9jeov.png"/>
        </td>
    </tr>
    <tr>
        <td>
            Web Page Demo 1: home page
            <img src="https://res.cloudinary.com/dscnnrudb/image/upload/v1728233417/portfolio/postimages/datalakehouse/7N_ZK74I7KL_4_J9R80FMY_cuonzj.jpg"/>
        </td>
        <td>
            Web Page Demo 2: sales and graphs
            <img src="https://res.cloudinary.com/dscnnrudb/image/upload/v1728233416/portfolio/postimages/datalakehouse/N_Y5LC__L6CP_H_2_39PN_P_d015f7.png"/>
        </td>
    </tr>
    <tr>
        <td>
            Django Database
            <img src="https://res.cloudinary.com/dscnnrudb/image/upload/v1728233416/portfolio/postimages/datalakehouse/3_QX1J4Z1_X7Y4C_AA2Q0_O_jifwjt.png"/>
        </td>
    </tr>
    
</table>