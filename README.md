# Stock Market Analytics Data Pipeline

An end-to-end data engineering project that extracts stock market data, loads it into Snowflake, transforms it using dbt, and prepares analytics-ready tables for BI dashboards.

## Tech Stack

- Python
- Apache Airflow
- Snowflake
- dbt
- Docker
- Preset / Tableau

## Project Overview

This pipeline automates the flow of stock market data from ingestion to analytics. Airflow orchestrates the workflow, Snowflake stores raw and transformed data, dbt manages SQL transformations and snapshots, and BI tools are used to visualize trends and insights.

## Architecture

1. Extract stock market data using Python.
2. Load raw data into Snowflake.
3. Run dbt transformations for analytics-ready models.
4. Track historical changes using dbt snapshots.
5. Visualize stock trends and metrics using a BI dashboard.

## Repository Structure

```text
.
├── dags/
│   ├── stock_market_etl.py
│   └── build_elt_with_dbt.py
├── stock_pipeline/
│   ├── models/
│   ├── snapshots/
│   ├── dbt_project.yml
│   └── profiles.yml
├── config/
├── plugins/
├── docker-compose.yaml
├── docker-compose-min.yaml
└── README.md
cat > README.md << 'EOF'
# Stock Market Analytics Data Pipeline

An end-to-end data engineering project that extracts stock market data, loads it into Snowflake, transforms it using dbt, and prepares analytics-ready tables for BI dashboards.

## Tech Stack

- Python
- Apache Airflow
- Snowflake
- dbt
- Docker
- Preset / Tableau

## Project Overview

This pipeline automates the flow of stock market data from ingestion to analytics. Airflow orchestrates the workflow, Snowflake stores raw and transformed data, dbt manages SQL transformations and snapshots, and BI tools are used to visualize trends and insights.

## Architecture

1. Extract stock market data using Python.
2. Load raw data into Snowflake.
3. Run dbt transformations for analytics-ready models.
4. Track historical changes using dbt snapshots.
5. Visualize stock trends and metrics using a BI dashboard.

## Repository Structure

```text
.
├── dags/
│   ├── stock_market_etl.py
│   └── build_elt_with_dbt.py
├── stock_pipeline/
│   ├── models/
│   ├── snapshots/
│   ├── dbt_project.yml
│   └── profiles.yml
├── config/
├── plugins/
├── docker-compose.yaml
├── docker-compose-min.yaml
└── README.md
