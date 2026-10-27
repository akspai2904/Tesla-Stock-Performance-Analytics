# Tesla Stock Performance Analytics | Tableau

## Project Overview

This project presents an interactive Tableau dashboard analyzing Tesla (TSLA) stock performance from **July 2010 to August 2024**.

The dashboard combines historical stock returns, price volatility, drawdowns, trading activity, and candlestick patterns to provide a comprehensive view of Tesla's stock performance and investment risk.

The analysis demonstrates the use of Tableau for financial data visualization, time-series analysis, calculated metrics, and interactive business intelligence reporting.

## Dashboard Preview

![Tesla Stock Performance Analytics Dashboard](Tesla%20Stock%20Dashboard.png)

**[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/akshata.pai/viz/TeslaStockPerformanceAnalytics/TeslaStockDashboard)**

## Project Objectives

- Evaluate Tesla's historical stock performance using total returns and compound annual growth rate (CAGR).
- Analyze monthly stock returns to identify positive and negative performance periods.
- Measure downside risk through historical drawdown analysis.
- Examine changes in market volatility using a six-month rolling volatility indicator.
- Explore the relationship between trading volume and monthly stock returns.
- Visualize historical stock price movements using monthly candlestick charts.

## Key Performance Indicators

| KPI | Value | Description |
|---|---|---|
| Total Stock Return | 15,388.22% | Overall percentage change in stock value across the analysis period |
| Annualized Return (CAGR) | 43.04% | Compound annual growth rate over the historical period |
| Maximum Drawdown | -67.72% | Largest peak-to-trough percentage decline |
| Annualized Volatility | 63.36% | Annualized measure of historical return variability |

These metrics summarize Tesla's historical growth, volatility, and downside risk.

## Dashboard Visualizations

### 1. Monthly Stock Returns Heatmap

- Displays monthly stock returns across years from 2010 to 2024.
- Uses green and red color encoding to distinguish positive and negative returns.
- Helps identify seasonal patterns, high-return months, and periods of negative performance.

### 2. Historical Stock Drawdown Analysis

- Tracks the percentage decline in Tesla's stock price from its previous historical peak.
- Highlights periods of sustained losses and market corrections.
- Provides a visual representation of downside risk.

### 3. Six-Month Rolling Volatility

- Measures changes in stock return variability over rolling six-month periods.
- Uses reference thresholds at 15% and 30% to distinguish volatility levels.
- Helps identify periods of elevated market uncertainty and comparatively stable performance.

### 4. Trading Volume vs. Monthly Returns

- Uses a scatter plot to examine the relationship between monthly trading volume and stock returns.
- Separates positive and negative returns through color encoding.
- Supports exploratory analysis of trading activity and market performance.

### 5. Monthly Candlestick Analysis

- Visualizes Tesla's historical monthly price movements.
- Displays opening, closing, high, and low stock prices.
- Highlights bullish and bearish price movements over time.

## Dataset

**Stock:** Tesla, Inc. (TSLA)  
**Analysis Period:** July 2010 – August 2024  
**Data Granularity:** Monthly observations

The dataset contains historical stock market information, including:

- Date
- Opening Price
- Highest Price
- Lowest Price
- Closing Price
- Adjusted Closing Price
- Trading Volume

Historical stock data was used to develop monthly performance metrics and financial visualizations in Tableau.

## Methodology

### Data Preparation

- Imported historical Tesla stock data into Tableau.
- Organized stock observations by month and year.
- Applied date-based aggregation for monthly analysis.
- Used adjusted closing prices for historical return calculations.
- Prepared the required fields for candlestick, volatility, and drawdown analysis.

### Financial Metrics

**Total Stock Return**

Measures the percentage change between the starting and ending stock prices.

**Compound Annual Growth Rate (CAGR)**

Measures the annualized compounded growth of Tesla's stock value across the analysis period.

**Maximum Drawdown**

Measures the largest decline from a historical stock price peak.

**Annualized Volatility**

Measures the variability of historical returns, expressed on an annualized basis.

**Six-Month Rolling Volatility**

Evaluates changes in return variability using a rolling six-month window.

### Tableau Development

The dashboard uses:

- Calculated Fields
- Table Calculations
- Level of Detail (LOD) Expressions
- Date-Based Aggregation
- Rolling Calculations
- Conditional Color Encoding
- Reference Lines
- KPI Cards
- Interactive Tooltips
- Dashboard Layout and Formatting

## Key Insights

**1. Significant long-term stock appreciation**

Tesla generated a total historical stock return of approximately 15,388%, reflecting substantial appreciation across the analysis period.

**2. High returns accompanied by substantial risk**

The 43.04% CAGR demonstrates strong historical compounded growth, while the -67.72% maximum drawdown highlights the potential severity of downside risk.

**3. Volatility varied considerably over time**

The rolling volatility chart shows periods of relatively stable performance alongside sharp increases in return variability.

**4. Monthly returns were highly variable**

The heatmap reveals both strong positive months and substantial negative months, demonstrating that historical stock performance was not consistent across periods.

**5. Trading activity did not guarantee positive returns**

The scatter plot shows positive and negative monthly returns across different trading-volume levels, illustrating that high trading activity alone does not ensure positive performance.

## Tools and Technologies

| Tool / Technique | Purpose |
|---|---|
| Tableau | Dashboard development and financial visualization |
| Excel | Historical stock data storage |
| Calculated Fields | Financial KPI development |
| Table Calculations | Rolling volatility and historical performance analysis |
| LOD Expressions | Monthly price aggregation |
| Data Visualization | Trend analysis, risk analysis, and interactive reporting |

## Project Files

The repository contains:

- **Tableau Packaged Workbook (`.twbx`)** — Tableau workbook containing the dashboard and supporting data.
- **Dashboard Screenshot (`.jpeg`)** — Preview of the completed dashboard.
- **README.md** — Project documentation.

## Interactive Dashboard

Explore the published dashboard:

[**Tesla Stock Performance Analytics — Tableau Public**](https://public.tableau.com/app/profile/akshata.pai/viz/TeslaStockPerformanceAnalytics/TeslaStockDashboard)

## Author

**Akshata Pai**

Business Intelligence | Data Analytics | Data Visualization

- [LinkedIn](https://www.linkedin.com/in/akshata-p-pai)
- [GitHub](https://github.com/akspai2904)
- [Tableau Public](https://public.tableau.com/app/profile/akshata.pai/vizzes)

---

*This project is intended for educational and portfolio purposes and does not constitute financial advice.*
