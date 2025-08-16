# Airflow
Automating a Weather Forecast ETL Pipeline with Apache Airflow, Postgres & Astronomer:

## Summary:
This project demonstrates how to build an **automated ETL pipeline** that extracts real-time weather forecast data from an API, transforms it into a structured format, and loads it into a **PostgreSQL database**. The pipeline is orchestrated using **Apache Airflow**, containerized with **Astronomer**, and designed to run on a scheduled basis.  

It provides a hands-on implementation of **Data Engineering best practices** such as workflow orchestration, data transformation, scheduling, and database integration.



## Project Objective:
- Automate the process of collecting weather data from a public API.  
- Clean, transform, and normalize raw JSON responses into a tabular structure.  
- Store processed data in **Postgres** for analytics and downstream usage.  
- Leverage **Apache Airflow DAGs** to schedule and monitor ETL jobs.  
- Use **Astronomer** for containerization, deployment, and scalable orchestration.  



## Tech Stack:
- **Python** – Data extraction and transformation logic  
- **Apache Airflow** – Workflow orchestration  
- **Astronomer** – Packaging & running Airflow in Dockerized environment  
- **PostgreSQL** – Data storage  
- **Docker** – Containerization  
- **Weather API** – Data source (e.g., Open-Meteo)  



## ETL Pipeline Workflow:
1. **Extract** – Fetch weather data from an external API.  
2. **Transform** – Parse JSON response, normalize data, handle missing values, and convert timestamps.  
3. **Load** – Insert cleaned data into **Postgres** tables.  
4. **Schedule** – Airflow DAG runs automatically (e.g., every 30 minutes).  
5. **Monitor** – Airflow UI provides visibility into task success/failure.  



## Conclusion:
This project shows how Apache Airflow + Astronomer + PostgreSQL can be combined to build a scalable, production-ready ETL pipeline. By automating data ingestion and transformation, organizations can rely on up-to-date weather insights for analytics, dashboards, or ML models.
