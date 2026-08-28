# Stock Price & Revenue Analysis: Tesla vs. GameStop

A Python data analysis project that compares historical stock performance and quarterly revenue data for Tesla and GameStop. The project demonstrates data collection, web scraping, data cleaning, and visualization in an end-to-end workflow.

## Project Overview

This project explores the relationship between two commonly used indicators of company performance:

- Historical stock prices
- Quarterly revenue

The analysis retrieves historical market data with `yfinance`, extracts quarterly revenue tables from web pages using `requests` and `BeautifulSoup`, cleans the resulting datasets, and visualizes stock-price and revenue trends for Tesla and GameStop.

## Objectives

- Retrieve historical stock data using `yfinance`
- Extract quarterly revenue data through web scraping
- Clean and prepare revenue data for analysis
- Visualize historical stock prices and revenue trends
- Compare the available financial data for Tesla and GameStop

## Technologies Used

- Python
- Pandas
- yfinance
- Requests
- BeautifulSoup
- Matplotlib
- Jupyter Notebook

## Project Workflow

### 1. Retrieve Historical Stock Data

Historical stock data is collected for:

- Tesla (`TSLA`)
- GameStop (`GME`)

The data is retrieved using the `yfinance` Python library and stored in Pandas DataFrames for analysis and visualization.

### 2. Extract Quarterly Revenue Data

Quarterly revenue data is collected from web pages using:

- `requests` to retrieve the HTML content
- `BeautifulSoup` to parse the HTML
- Pandas to organize the extracted tables

The analysis extracts the relevant quarterly revenue tables for both companies.

### 3. Clean the Revenue Data

The revenue datasets are prepared for analysis by:

- Removing currency symbols
- Removing comma separators
- Removing missing values
- Excluding empty revenue records

### 4. Visualize the Results

A reusable `make_graph` function is used to visualize:

- Historical closing stock prices
- Quarterly revenue data

Separate visualizations are produced for Tesla and GameStop.

## Project Structure

```text
.
├── stock_price_revenue_analysis_portfolio.ipynb
└── README.md
```

## How to Run

### 1. Clone the repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Install the required packages

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib nbformat
```

### 3. Open the notebook

```bash
jupyter notebook stock_price_revenue_analysis_portfolio.ipynb
```

Run the notebook cells in order.

## Skills Demonstrated

- Data acquisition
- API-based financial data retrieval
- Web scraping
- HTML parsing
- Data cleaning
- Pandas DataFrame manipulation
- Data visualization
- Reusable Python functions
- Jupyter Notebook workflows

## Data Sources

The notebook retrieves historical market data through `yfinance` and uses the revenue data pages referenced directly within the original analysis notebook.

## Notes

This project is intended as a data analysis portfolio project. Historical stock and revenue data may change depending on when the notebook is executed, and the availability or structure of external data sources may also affect results.

## Author

**Yunseo Jang**

Aspiring Data Analyst with experience in Python, SQL, data visualization, and analytical problem-solving.
