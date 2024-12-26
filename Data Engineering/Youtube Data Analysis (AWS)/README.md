# Youtube Data Engineering and analysis project

## Overview

In this Data Engineering Project, we have a data set of Olympic Sports from 2021 (Data source) and storing that data into Azure as raw data and perform the necessary Transformation and store the transformed data to a storage location, then we can do the Analytics/analysis of the transformed/cleaned data.

## Prerequisites

Directions or anything needed before running the project.

- Basic Knowledge on SQL and Python/PySpark
- Azure Account
- Good to have basic understanding about Azure Services

## How to Run This Project

Since this Project is compeletly cloud based, we don't need to any Program/Software to install in local system

1. Place the data source in Github repositoy
2. Setup Azure account (Free trial with credits)

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
