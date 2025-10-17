# Module 1, Clip 2: Data Ingestion

This module covers data ingestion techniques from multiple sources including CSV files and REST APIs.

## Files

- `Ingest_CSV.py`: Demonstrates CSV data loading and basic analysis
- `Ingest_API.py`: Shows how to fetch data from REST APIs
- `HRIS.csv`: Sample HRIS (Human Resources Information System) dataset

## What You'll Learn

- How to load and analyze CSV data
- REST API data ingestion techniques
- Working with different data formats
- Basic data exploration and validation

## Key Concepts

### CSV Data Ingestion
- Loading CSV files with pandas
- Basic data inspection (head, info, describe)
- Understanding data structure and types

### API Data Ingestion
- Making HTTP requests to REST APIs
- Parsing JSON responses
- Handling API responses and errors
- Working with real-time data (weather data)

## Usage

### CSV Ingestion
```bash
python Ingest_CSV.py
```

### API Ingestion
```bash
python Ingest_API.py
```

## API Example: Weather Data

The API example uses the Open-Meteo weather API to fetch current weather data for Miami, FL. This demonstrates:
- Constructing API URLs with parameters
- Making GET requests
- Parsing JSON responses
- Converting API data to DataFrames

## Sample Data

The `HRIS.csv` file contains sample human resources data that demonstrates:
- Employee information
- Data types and structures
- Basic statistical analysis

## Dependencies

- `pandas`: Data manipulation and analysis
- `requests`: HTTP library for API calls

## Learning Outcomes

After completing this module, you'll understand:
- How to load data from different sources
- API integration techniques
- Data validation and exploration
- Error handling in data ingestion
- Converting external data to pandas DataFrames
