# Trader Behavior vs Market Sentiment Analysis

## Overview

This project investigates the relationship between cryptocurrency trader behavior and the Bitcoin Fear & Greed Index by combining historical trading records with daily market sentiment data.

The project includes data preprocessing, feature engineering, exploratory analysis, trader segmentation, and strategy recommendations based on the insights obtained from the analysis.

---

## Objectives

- Analyze trader performance across different market sentiments (Fear, Neutral, and Greed).
- Examine how trading behavior changes under varying market conditions.
- Segment traders based on their trading characteristics.
- Generate data-driven insights and actionable trading strategies.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---
## How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries:
   - pandas
   - numpy
   - matplotlib
   - seaborn
4. Ensure the required datasets are available in the project directory. The Fear & Greed dataset is included in this repository, while the historical trading dataset should be added separately.
5. Run the notebook cells sequentially from top to bottom.

## Methodology

The analysis was carried out in the following stages:

- Loaded the historical trading dataset and the Bitcoin Fear & Greed Index dataset.
- Performed data cleaning by checking for missing values, duplicates, and converting timestamps into a common daily date format.
- Merged both datasets using the date column to associate each trade with the corresponding daily market sentiment.
- Engineered key metrics such as win rate, average trade size, trade frequency, drawdown proxy, long/short ratio, and trader-level performance measures.
- Compared trading performance across Fear, Neutral, and Greed market conditions using metrics including average PnL, win rate, average trade size, and drawdown proxy.
- Analyzed changes in trading behavior by examining trade frequency, position size, and long/short bias across different market sentiments.
- Segmented traders based on trading frequency, trading exposure, and trading consistency to identify distinct trading patterns.
- Summarized the findings using visualizations and proposed practical strategy recommendations based on the observed results.
---
  

## Key Findings

- Greed periods generated the highest average profit per trade but also exhibited the highest downside risk.
- Traders allocated larger average position sizes during Fear periods.
- Infrequent traders achieved higher average profit per trade than frequent traders, suggesting that selective trading may be more effective than excessive trading activity.

---
## Strategy Recommendations

1. **Adopt sentiment-based risk management:** During Greed periods, maintain stricter risk controls and avoid unnecessarily increasing exposure, as these periods were associated with the largest downside risk.

2. **Prioritize trade quality over trade quantity:** The analysis indicates that traders executing fewer, well-planned trades achieved better average profitability than those trading more frequently.

   
## Repository Contents

```
Trader_Behavior_Market_Sentiment_Analysis.ipynb
README.md
fear_greed_index.csv
images/(project visualisations)
```

> **Note:** The historical trading dataset has not been included in this repository due to its large file size.

---

## Author

**Khushi**
