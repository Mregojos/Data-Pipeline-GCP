# Data Pipeline on GCP

---
    GCP Services for Data Engineering
        > Data Warehouse: 
            BigQuery
        > Data Lake: 
            Cloud Storage
        > Data Transformation:
            Dataflow (Managed Apache Beam)
            Dataproc (Managed Apache Spark)
            Cloud Functions (Event-driven Serverless)
        > Data Transformation (Open-Source):
            Python
            PySpark
            Pandas
        > Data Orchestration:
            Composer (Managed Apache Airflow)
        > Data Orchestration (Open-Source)
            Prefect
            Airflow
        > Database
            SQL: Cloud SQL, Spanner
            NoSQL: BigTable
        > Data Visualization
            Looker
            Looker Studio (Free Version) 
            
---
    Data Pipelines:
        1. ETL
            a. Unprocessed Data -> Data Processing -> Processed Data (Data Warehouse)
            b. Unprocessed Data -> Data Processing -> Processed Data (Data Lake)
        2. ELTL
            a. Unprocessed Data -> Unprocessed Data (Data Lake) -> Data Processing -> Processed Data (Data Warehouse)

    Project:
        ELTL: Unprocessed Data -> Unprocessed Data (Data Lake) -> Data Processing -> Processed Data (Data Warehouse) for Analytics & Processed Data (Data Lake) for Archieving -> Data Visualization

        Questions:
            1. What's the data? Goal and Purpose?
            2. Where's the unprocessed data stored?
            3. Data Processing?
                What tool to use for data processing?
                    * Python
                What'll be data processing strategy?
            4. Data Lake?
                * Cloud Storage
            5. Data Warehousing?
                BigQuery
            6. Data Visualization Tool?
                Looker Studio