# US Mutual Funds & ETFs Financial Analytics Warehouse

## Overview

This project builds a financial analytics data warehouse for U.S. mutual funds and ETFs using DuckDB, dbt, and Python. The system enables efficient querying, transformation, and analysis of large-scale financial datasets.

## Tech Stack

* DuckDB
* dbt Core
* Python (Pandas, Dask)
* Jupyter Notebooks

## Data Pipeline

1. Raw financial data is ingested from CSV files using Python
2. Data is stored in a DuckDB warehouse
3. dbt transforms raw data into structured analytical models
4. Analytical queries and insights are generated in notebooks

## Project Structure

* `data/raw/` – Source datasets
* `dbt/` – Data transformation models and pipeline
* `notebooks/` – Data ingestion and analysis
* `warehouse/` – DuckDB database file

## Key Features

* Structured financial data warehouse design
* ETL pipeline using Python and dbt
* Scalable querying with DuckDB
* End-to-end analytics workflow
