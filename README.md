### **README.md**

---

# **Bitcoin Market Sentiment vs. Trader Performance Analysis**

## **Overview**

This repository contains a data science project that explores the relationship between the **Bitcoin Fear & Greed Index** and historical trading performance on the **Hyperliquid** platform. The goal is to uncover how market psychology influences profitability, risk management, and asset-specific performance (BTC vs. Altcoins).

## **Dataset Description**

The analysis is built using two primary datasets:

1. **Bitcoin Market Sentiment Dataset:** Daily historical classifications (Fear, Greed, Neutral, etc.).
2. **Hyperliquid Historical Trader Data:** Comprehensive logs including account addresses, symbols, execution prices, trade sizes, sides (Long/Short), leverage, and Closed PnL.

## **Key Objectives**

* **Sentiment Correlation:** Determine which market moods yield the highest Profit Factors and Win Rates.
* **Risk Analysis:** Analyze how "Notional Value" (capital commitment) fluctuates during market extremes.
* **Smart Money Insights:** Compare the strategic behavior of the Top 10% most profitable traders against the general market.
* **Asset Sensitivity:** Evaluate if Altcoins or Bitcoin provide better risk-adjusted returns during specific sentiment phases.

## **Project Structure**

* `DS_Task.ipynb`: The primary Jupyter Notebook containing data cleaning, merging, statistical analysis, and visualizations.
* `data/`: (Optional) Folder for storing the raw CSV files (`historical_data.csv` and `fear_greed_index.csv`).
* `Report.pdf`: A summary document detailing the final insights and strategic recommendations.

## **Key Findings**

* **Profitability Peaks:** Market "Greed" periods showed the highest Profit Factor (7.23), while "Neutral" phases were the least profitable.
* **Capital Extremes:** Traders tend to double their capital commitment (Notional Value) during periods of "Fear" or "Extreme Greed."
* **The Hedging Edge:** Top-performing traders maintain a balanced 1:1 Long/Short ratio during "Extreme Greed," whereas less profitable traders tend to exhibit heavy directional bias.

## **Installation & Usage**

1. Clone the repository:
```bash
git clone https://github.com/your-username/sentiment-trading-analysis.git

```


2. Install dependencies:
```bash
pip install pandas matplotlib seaborn numpy

```


3. Run the notebook:
```bash
jupyter notebook DS_Task.ipynb

```



## **Technologies Used**

* **Python** (Pandas, NumPy)
* **Matplotlib & Seaborn** (Data Visualization)
* **Google Colab** (Interactive Analysis)
* **Gemini AI for Code help** (Interactive Analysis)
---
