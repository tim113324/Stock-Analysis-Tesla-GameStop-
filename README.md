# Tesla and GameStop Stock and Revenue Analysis

This project performs a historical stock price and revenue analysis for two major companies: Tesla (TSLA) and GameStop (GME). The analysis is done using data from Yahoo Finance and revenue data from web scraping.

## Project Overview

In this notebook, we:
1. **Fetch stock data**: Using `yfinance`, we gather historical stock price data for both Tesla and GameStop.
2. **Extract revenue data**: Using BeautifulSoup, we scrape Tesla and GameStop's historical revenue data from a provided URL.
3. **Data cleaning**: We clean and preprocess the revenue data to make it usable for visualization.
4. **Data visualization**: Using Plotly, we generate interactive graphs to visualize both the stock price and revenue data over time.

### Key Features:
- **Historical Stock Price**: Visualize stock price trends over time for both Tesla and GameStop.
- **Historical Revenue**: Visualize revenue trends for both companies.
- **Interactive Graphs**: The data is visualized using Plotly, which generates interactive plots that can be explored further.

## Installation

To run this notebook on your local machine, you'll need the following Python libraries:

- `pandas`
- `yfinance`
- `requests`
- `beautifulsoup4`
- `plotly`
- `IPython`

You can install the required libraries by running the following command:

```bash
pip install pandas yfinance requests beautifulsoup4 plotly ipython
```

## How to Use and Results

1. **Clone the repository**:  
```bash
git clone https://github.com/tim113324/Stock-Analysis-Tesla-GameStop-.git
```

2. **Run the Notebook**:  
Navigate to the cloned directory and open the notebook:

```bash
jupyter notebook Stock-Analysis.ipynb
```

3. **Explore the Results**:  
The notebook will generate interactive plots that display the stock prices and revenue data for both Tesla and GameStop.

### Results Visualized:
- Tesla's Stock Price vs. Revenue
- GameStop's Stock Price vs. Revenue

You can adjust the analysis period, filter data by date, and explore different visualizations.

---
