\# Credit Risk Assessment Pipeline



\## Project Overview

This project implements an end-to-end Credit Risk Assessment Pipeline on Microsoft Azure using the Medallion Architecture (Bronze, Silver, Gold).



\## Architecture



\- Azure Data Lake Storage Gen2

\- Azure Data Factory

\- Azure Databricks

\- Delta Lake

\- dbt

\- PySpark

\- SQL

\- Git \& GitHub



\## Project Structure



```

ARCHITRCTURE/

DATASETS/

DBT/

DEVELOPMENT/

Trained\_Dataset/

```



\## Workflow



1\. Upload raw CSV files to ADLS Gen2

2\. Convert CSV files into Parquet using Azure Data Factory

3\. Load data into Bronze Layer

4\. Clean and transform data in Silver Layer

5\. Build analytical models in Gold Layer using dbt

6\. Perform data quality testing

7\. Create dashboards and KPIs



\## Technologies Used



\- Azure Data Lake Storage Gen2

\- Azure Data Factory

\- Azure Databricks

\- PySpark

\- Delta Lake

\- dbt

\- SQL

\- Git

\- GitHub



\## Dataset



The project uses a Credit Risk Assessment dataset containing:



\- Applicant Profiles

\- Credit Applications

\- Credit History

\- Loan Details

\- Economic Indicators



\## Author



Pradeep Kumar

