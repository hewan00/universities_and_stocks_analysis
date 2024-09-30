# Universities and Stock Data Analysis

## Overview

This project uses APIs to fetch and analyze university and stock data using Python, JSON, and Pandas.

### Sections:
1. **University Data Analysis**: 
    - Fetches data from the Hipolabs Universities API.
    - Parses JSON responses and converts them into Pandas DataFrames.
    - Analyzes the data to visualize the number of universities per state or country.
    
2. **Stock Data Fetcher**:
    - Prompts the user to input stock symbols.
    - Fetches stock data using the Finance API.
    - Displays key stock information such as company name and current market price.

## Installation

### Prerequisites:
- Python 3.x
- Pip (Python package manager)

### Steps to Run:
1. Clone the repository.
    ```bash
    git clone https://github.com/yourusername/universities_and_stocks_analysis.git
    cd universities_and_stocks_analysis
    ```
   
2. Install the required Python packages.
    ```bash
    pip install -r requirements.txt
    ```

3. Run the university data analysis script:
    ```bash
    python university_data_analysis.py
    ```

4. Run the stock data fetcher script:
    ```bash
    python stock_data_fetcher.py
    ```

## Note:
To fetch stock data, you'll need to get an API key from [Finance API](https://financeapi.net/) and add it to the `stock_data_fetcher.py` file in place of `"yourkey"`.

