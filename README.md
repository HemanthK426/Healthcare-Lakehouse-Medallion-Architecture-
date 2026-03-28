# 🏥 Healthcare Data Lakehouse Pipeline (Medallion Architecture)

## 📌 Problem Statement

Healthcare organizations generate large volumes of patient and claims data. This project builds a scalable data pipeline to ingest, clean, and transform raw healthcare data into analytics-ready datasets.

## 🏗️ Architecture

* Bronze Layer: Raw ingestion from CSV/JSON into S3
* Silver Layer: Data cleaning, schema enforcement, deduplication
* Gold Layer: Aggregated datasets for reporting (e.g., patient readmission rates)

## ⚙️ Tech Stack

* AWS S3
* Apache Spark (PySpark)
* Delta Lake
* Apache Airflow
* Python

## 🔄 Data Flow

1. Raw patient data ingested into Bronze layer
2. Data cleaned and validated into Silver tables
3. Business aggregations created in Gold layer

## ✅ Key Features

* Schema enforcement & evolution
* Data quality checks
* Incremental processing
* Partitioned storage for performance

## 📊 Sample Use Cases

* Patient readmission analysis
* Claims cost analysis
* Hospital performance metrics

## 🚀 How to Run

1. Upload sample data to `/data/raw`
2. Run ingestion script
3. Execute transformation notebooks
4. Trigger Airflow DAG

## 📈 Outcome

* Scalable data pipeline design
* Reduced data processing time
* Analytics-ready datasets for BI tools
