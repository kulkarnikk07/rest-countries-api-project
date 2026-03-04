# 🌍 REST Countries API — Data Extraction Project

## Overview
This project demonstrates how to interact with the [REST Countries API](https://restcountries.com/)
to fetch, extract, and analyze country data using Python and Pandas.

## Features
- Fetches data for all 250+ countries
- Covers multiple API endpoints (all, name, region, language, capital)
- Extracts and structures data into Pandas DataFrames
- Saves results to CSV files

## Tech Stack
- Python 3.14
- Jupyter Notebook
- `requests` library
- `pandas` library

## API Endpoints Used
| Endpoint | Purpose |
|---|---|
| `/all?fields={fields}` | Fetch max 10 countries fields |
| `/name/{name}` | Search by country name |
| `/region/{region}` | Filter by region |
| `/lang/{language}` | Filter by language |
| `/capital/{capital}` | Search by capital |

## How to Run
1. Clone the repo: `git clone <your-repo-url>`
2. Create a virtual environment: `python -m venv venv`
3. Activate it: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Mac/Linux)
4. Install dependencies: `pip install -r requirements.txt`
5. Open `rest_countries.ipynb` in VS Code or Jupyter

## Project Structure
```
rest-countries-project/
│
├── rest_countries.ipynb   # Main Jupyter Notebook
├── countries_data.csv     # Full dataset (all countries)
├── asia_countries.csv     # Asia subset
├── requirements.txt       # Python dependencies
└── README.md
```
