#  ETL Pipeline

## Overview
This project involves building an ETL (Extract, Transform, Load) pipeline to process real-world data. i have extracted data from a webpage, transformed it using Python and Pandas, and loaded it into CSV files and an SQL database.

---



## Tools & Libraries
- **Python 3**
- `requests` — for fetching web content
- `BeautifulSoup` (from `bs4`) — for web scraping HTML content
- `pandas` — for data manipulation and transformation
- `numpy` — for numeric operations
- `sqlite3` — for SQL database operations

---

## Project Tasks

###  Data Extraction
- Scrape data from webpages using requests and BeautifulSoup
- extract structured tables and relevant information
- Handle missing or inconsistent HTML elements

###  Data Transformation
- Clean and preprocess raw data
- Standardize formats and units
- Examples: USD → EUR, Millions → Billions
- Rename columns and handle null values
- Prepare data for storage

###  Data Loading
- Export cleaned data to CSV files
- Load data into SQLite database
- Create tables and insert records using Python SQL commands

###  SQL Query
- Run SQL queries from Python
- Validate data integrity
- analyze loaded data

###  Logging & Monitoring
- Track progress at each ETL stage
- Log messages for extraction, transformation, loading, and SQL execution
- improve debugging and pipeline maintainability
