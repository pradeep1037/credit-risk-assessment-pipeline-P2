\# 🚀 Credit Risk Assessment Pipeline on Azure



!\[Azure](https://img.shields.io/badge/Azure-Cloud-blue?logo=microsoftazure)

!\[Databricks](https://img.shields.io/badge/Databricks-ETL-red?logo=databricks)

!\[PySpark](https://img.shields.io/badge/PySpark-Data%20Engineering-orange)

!\[Delta Lake](https://img.shields.io/badge/Delta-Lake-green)

!\[dbt](https://img.shields.io/badge/dbt-Transformation-orange)

!\[GitHub](https://img.shields.io/badge/Git-Version%20Control-black)



\---



\# 📌 Project Overview



The \*\*Credit Risk Assessment Pipeline\*\* is an end-to-end Azure Data Engineering project that processes raw credit risk data into analytics-ready datasets using the \*\*Medallion Architecture (Bronze → Silver → Gold)\*\*.



The project demonstrates how modern Azure services can be integrated to build scalable, reliable, and production-ready ETL pipelines for financial data processing.



\---



\# 🏗️ Solution Architecture



<p align="center">

<img src="ARCHITECTURE/credit\_risk\_analysis\_HLD.png" width="900">

</p>



\---



\# 🥉🥈🥇 Medallion Architecture



<p align="center">

<img src="ARCHITECTURE/Medallion\_Architecture.png" width="900">

</p>



The project follows the Medallion Architecture to improve data quality and support analytical workloads.



\### Bronze Layer

\- Ingest raw source files

\- Preserve original data

\- Add audit columns

\- Perform schema validation



\### Silver Layer

\- Clean and standardize data

\- Remove duplicates

\- Handle null values

\- Apply business transformations



\### Gold Layer

\- Create business-ready datasets

\- Build Fact \& Dimension tables

\- Generate KPIs

\- Support dashboards and reporting



\---



\# ☁️ Azure Services Used



| Service | Purpose |

|----------|----------|

| Azure Data Lake Storage Gen2 | Raw \& Processed Data Storage |

| Azure Data Factory | Batch Data Ingestion |

| Azure Databricks | Data Processing \& Transformation |

| Delta Lake | Reliable Data Storage |

| dbt | Data Modeling |

| GitHub | Version Control |



\---



\# ⚙️ Technology Stack



\- Azure Data Factory

\- Azure Data Lake Storage Gen2

\- Azure Databricks

\- PySpark

\- Delta Lake

\- SQL

\- dbt

\- Git \& GitHub



\---



\# 📂 Repository Structure



```text

Credit-Risk-Assessment-Pipeline

│

├── ARCHITECTURE

│   ├── High Level Design

│   ├── Low Level Design

│   ├── Medallion Architecture

│   └── Star Schema

│

├── DATASETS

│   ├── applicant\_profiles.csv

│   ├── credit\_applications.csv

│   ├── credit\_history.csv

│   ├── economic\_indicators.csv

│   └── loan\_details.csv

│

├── DEVELOPMENT

│   ├── Bronze

│   ├── Silver

│   ├── SQL

│   ├── Audit

│   └── Logger

│

├── DBT

│   ├── Models

│   ├── Tests

│   ├── KPI

│   └── Dashboards

│

├── Trained\_Dataset

│

└── README.md

```



\---



\# 🔄 Pipeline Workflow



```text

CSV Files

&#x20;   │

&#x20;   ▼

Azure Data Lake Storage Gen2

&#x20;   │

&#x20;   ▼

Azure Data Factory

&#x20;   │

&#x20;   ▼

Parquet Files

&#x20;   │

&#x20;   ▼

Azure Databricks

&#x20;   │

&#x20;   ▼

Bronze Layer

&#x20;   │

&#x20;   ▼

Silver Layer

&#x20;   │

&#x20;   ▼

Gold Layer (dbt)

&#x20;   │

&#x20;   ▼

Business Analytics \& Reporting

```



\---



\# 📊 Dataset Information



The project processes the following datasets:



\- Applicant Profiles

\- Credit Applications

\- Credit History

\- Loan Details

\- Economic Indicators



These datasets are transformed to assess customer creditworthiness and support risk analysis.



\---



\# ✨ Key Features



\- End-to-End Azure Data Engineering Pipeline

\- Medallion Architecture

\- Batch ETL Processing

\- PySpark Transformations

\- Delta Lake Storage

\- dbt Data Modeling

\- Data Quality Validation

\- SQL Analytics

\- Git Version Control



\---



\# 📈 Data Processing Stages



\### Bronze

\- Raw Data Ingestion

\- Metadata Capture

\- Schema Validation



\### Silver

\- Data Cleaning

\- Type Casting

\- Data Standardization

\- Business Rule Implementation

\- Deduplication



\### Gold

\- Star Schema

\- Fact Tables

\- Dimension Tables

\- KPI Models

\- Dashboard Data



\---



\# 🧪 Data Quality Testing



The project includes validation for:



\- Duplicate Records

\- Null Values

\- Credit Score Validation

\- Loan Amount Validation

\- Relationship Integrity

\- Region Validation



\---



\# 🚀 Future Enhancements



\- Power BI Dashboard

\- Azure DevOps CI/CD Pipeline

\- Apache Airflow Scheduling

\- Azure Key Vault Integration

\- Pipeline Monitoring \& Alerts

\- Automated Unit Testing



\---



\# 👨‍💻 Author



\*\*Pradeep Kumar\*\*



\*\*Data Engineer\*\*



\*\*Skills:\*\* Azure • Azure Data Factory • Azure Databricks • PySpark • SQL • dbt • Delta Lake • Git

