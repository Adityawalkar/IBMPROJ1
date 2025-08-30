# Tesla & GameStop Stock and Revenue Analysis

This project is part of the Coursera/IBM Data Science Labs. It extracts stock price data for **Tesla (TSLA)** and **GameStop (GME)** using `yfinance`, scrapes quarterly revenue data from Macrotrends, and visualizes stock price trends.

---

## 📂 Project Structure
```
├── tesla_gme_assignment.ipynb   # Jupyter Notebook with full analysis (Q1–Q6)
├── tesla_data.csv               # Tesla stock data (downloaded via yfinance)
├── tesla_revenue.csv            # Tesla revenue data (scraped)
├── gme_data.csv                 # GameStop stock data (downloaded via yfinance)
├── gme_revenue.csv              # GameStop revenue data (scraped)
├── tesla_price.png              # Tesla stock price plot
├── gme_price.png                # GameStop stock price plot
└── README.md                    # This file
```

---

## 🛠️ Requirements
Install dependencies if not already available in your environment:
```bash
pip install yfinance pandas requests beautifulsoup4 lxml matplotlib
```

---

## 🚀 How to Run
1. Open **`tesla_gme_assignment.ipynb`** in Jupyter Notebook, JupyterLab, or Watson Studio.
2. Run all cells sequentially.
3. Take screenshots of the required outputs for submission:
   - **Q1:** First 5 rows of Tesla stock (`tesla_data.head()`)
   - **Q2:** Last 5 rows of Tesla revenue (`tesla_revenue.tail()`)
   - **Q3:** First 5 rows of GameStop stock (`gme_data.head()`)
   - **Q4:** Last 5 rows of GameStop revenue (`gme_revenue.tail()`)
   - **Q5:** Tesla stock price graph
   - **Q6:** GameStop stock price graph

---

## 📊 Features
- **Stock Data (yfinance):** Downloads historical TSLA and GME stock data.
- **Revenue Data (Web Scraping):** Extracts quarterly revenue tables from Macrotrends using BeautifulSoup and pandas.
- **Visualization:** Plots closing price vs time with `matplotlib`.
- **Resilient Scraping:** Uses headers + fallback search to avoid missing tables.
- **Export:** Saves stock/revenue data as CSV and plots as PNG.

---
