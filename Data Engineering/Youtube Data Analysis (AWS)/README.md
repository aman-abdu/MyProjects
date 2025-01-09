# Youtube Data Engineering and analysis project

## Overview

In this Data Engineering Project, we have a data set of Youtube data for a particular year and storing that into AWS S3 as data source. we are using S3 for storage and transformed data storage with 3 different stages. Finally once the raw data transformed full we will make use Athena to get SQL analytical insights and quickSight to build a dashboard.  
          In this Project we can learn about
              - Building data lake from scratch
              - understand data lake and data warehouse
              - Good to have basic understanding about Azure Service

## Prerequisites

Directions or anything needed before running the project.

- Basic Knowledge on SQL and Python/PySpark
- AWS Account
- Good to have basic understanding about AWS Services

## How to Run This Project

Since this Project is compeletly cloud based, we don't need to any Program/Software to install in local system

2. Setup AWS account

### Data Architecture

![Example architecture image](images/arch.png)

As per above Architecture, we have data source placed in Github repostiry, from there we ingest data into data alke storage using Azure Data factory by creating pipleines here we loading data as raw data, then we use Azure databricks to do soe basic transformation and clean the data. then we load transformed data/cleansed data to azure data lake storage. then we use Azure synapse analytics to get the clean data and perform some analytics using SQL queries, so we can create dashboards in Data analysis tools like Power BI or Tableau

### End-to-End Data Pipeline

![alt-pipeline-image](images/snip3.png)

### Data Visualization

![alt-data-visuaization](images/snip1.png)

![alt-data-visuaization](images/snip2.png)

## Lessons Learned

It's good to reflect on what you learned throughout the process of building this project. Here you might discuss what you would have done differently if you had more time/money/data. Did you end up choosing the right tools or would you try something else next time?

## Contact

Please feel free to contact me if you have any questions at: LinkedIn, Twitter
