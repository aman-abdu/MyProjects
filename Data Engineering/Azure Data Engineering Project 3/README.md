# Azure Data Engineering Project

## Overview

In this End-to-End Data Engineering Project, we have a data set of Car Sales data as Data source, which is loaded in github repository and we then ingest the data into SQL database with help of ETL pipeline in data factory. We will perform data transformation using databricks and this is achieved by following Medallion architecture to process and analyze car sales data. this project focuses on incremental data loading, Slowly changing dimensional (SCD Type-1), star schema design to transform data to analytical-ready insights.

## Prerequisites

- Basic Knowledge on SQL and Python/PySpark
- Azure Account
- Good to have basic understanding about Azure Services (ADF, databricks, data lake)

## Tools/Technologies Used

1. Azure SQL Database -> Storing raw data from Github source
2. Azure Data Factory -> Builting ETL pipelines
3. Azure Databricks -> Data transformation
4. Azure Data lake gen2 -> data storage and for transformation layers (Bronzr, Silver and Gold) 

### Data Architecture

![Example architecture image](images/architecture.png)

- we have data source placed in Github repostiry, from there we ingest data to SQL database using Data factory which is capable of Incremental data loading.
- Incremental Data loading ETL will then transfer the raw data into bronze layer container in Azure Data Lake gen2.
- Then we use Azure databricks to perfrom the transformations and place accordingly in Silver and Gold layer of ADLS.
- The final transformation into gold layer, we have implemented Star Schema, segregating one big table data into Fact and Dimension tables to ensure clean and analytical-ready datasets with SCD Type-1.

### End-to-End Data Pipeline

![alt-pipeline-image](images/etl_pipeline.png)

![alt-pipeline-image](images/etl2.png)

### Data Visualization

![alt-data-visuaization](images/final_analysis.png)

## Lessons Learned

It's good to reflect on what you learned throughout the process of building this project. Here you might discuss what you would have done differently if you had more time/money/data. Did you end up choosing the right tools or would you try something else next time?

## Contact

Please feel free to contact me if you have any questions at: LinkedIn, Twitter
