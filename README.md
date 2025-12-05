# 📊 Tesla & GameStop Stock Analysis Dashboard

Final project for IBM Data Analyst Professional Certificate - Analyzing historical stock price and revenue data for Tesla (TSLA) and GameStop (GME).

## 🎯 Project Overview

This project extracts, analyzes, and visualizes historical stock data and quarterly revenue information for two notable companies:
- **Tesla (TSLA)**: Electric vehicle and clean energy company
- **GameStop (GME)**: Video game retailer (famous for the 2021 short squeeze)

## 📈 Key Features

- **Stock Price Extraction**: Uses `yfinance` API to retrieve historical stock prices
- **Revenue Data Scraping**: Web scraping with BeautifulSoup to extract quarterly revenue data
- **Data Cleaning**: Handles missing values, removes special characters, and converts data types
- **Interactive Visualizations**: Dual-axis plots showing stock price and revenue trends over time

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries**:
  - `yfinance` - Stock market data
  - `pandas` - Data manipulation
  - `BeautifulSoup4` - Web scraping
  - `matplotlib` - Data visualization
  - `requests` - HTTP requests

## 📁 Project Structure
```
├── README.md                   # Project documentation
├── TSLA_GME_Analysis.ipynb     # Main Jupyter notebook                   
├── gitigrone                   # Python dependencies 
└── requirements.txt            # Python dependencies
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install yfinance pandas beautifulsoup4 matplotlib requests
```

### Installation

1. [Repository](https://github.com/78381507/TSLA_GME_Analysis.ipynb/blob/main/README.md)

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook TSLA_GME_Analysis.ipynb
```

## 📊 Visualizations

The project generates two comprehensive dashboards:

### Tesla Dashboard
- Historical stock price (2010-2021)
- Quarterly revenue growth
- Clear visualization of Tesla's exponential growth phase

### GameStop Dashboard
- Historical stock price showing the 2021 short squeeze
- Quarterly revenue trends
- Analysis of the retail trading phenomenon

## 🔍 Key Insights

- **Tesla**: Demonstrates consistent revenue growth alongside stock price appreciation
- **GameStop**: Shows the dramatic 2021 short squeeze event (stock price reached ~$80)
- Both visualizations include data up to June 2021

## 👨‍💻 Author

**François Tilkin**
- Data Analyst | Data Engineer
- IBM Data Analyst Professional Certificate
- [LinkedIn](www.linkedin.com/in/françois-tilkin-1667b138a)
- [Email](tilkinanalytics@gmail.com)

## 📝 License

This project is part of the IBM Data Analyst Professional Certificate program.
---

⭐ If you found this project useful, please consider giving it a star!
