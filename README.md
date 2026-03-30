# Database to DataFrame: PostgreSQL + Pandas Data Ingestion Pipeline

## Technology Stack
- **Database**: PostgreSQL 17
- **GUI Tool**: pgAdmin 4
- **Data Library**: Pandas + PyArrow
- **ORM / Engine**: SQLAlchemy 2.0
- **Drivers**: psycopg2, psycopg3, ADBC
- **Environment**: Jupyter Notebook + uv

## Project Structure
- `approach1_psycopg2.ipynb` — Legacy: psycopg2 + SQLAlchemy
- `approach2_psycopg3.ipynb` — Modern: psycopg3 + SQLAlchemy
- `approach3_adbc.ipynb` — Fastest: ADBC Driver
- `phase3_pandas_functions.ipynb` — Pandas DB Functions
- `example.env` — Environment variables template

## Setup
1. Copy `example.env` to `.env` and fill in your credentials
2. Run `uv sync` to install dependencies
3. Run `jupyter notebook` to open the notebooks