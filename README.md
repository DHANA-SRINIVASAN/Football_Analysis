# Football Data Engineering

This Python-based project crawls data from Wikipedia using Apache Airflow, cleans it and pushes it Azure Data Lake for processing.

## Table of Contents

1. [System Architecture](#architecture)
2. [Requirements](#requirements)
3. [Getting Started](#getting-started)
4. [Running the Code With Docker](#running-the-code-with-docker)
5. [How It Works](#how-it-works)

## System Architecture
![system_architecture.png](https://github.com/DHANA-SRINIVASAN/Football_Analysis/blob/main/architecture.jpeg)

## Requirements
- Python 3.9 (minimum)
- Docker
- PostgreSQL
- Apache Airflow 2.6 (minimum)

## Getting Started

1. Clone the repository.
   ```bash
   git clone https://github.com/airscholar/FootballDataEngineering.git
   ```

2. Install Python dependencies.
   ```bash
   pip install -r requirements.txt
   ```
   
## Running the Code With Docker

1. Start your services on Docker with
   ```bash
   docker compose up -d
   ``` 
2. Trigger the DAG on the Airflow UI.

## How It Works
1. Fetches data from Wikipedia.
2. Cleans the data.
3. Transforms the data.
4. Pushes the data to Azure Data Lake.
