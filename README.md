# trader-sentiment-analysis
Analysis of trader behavior vs market sentiment with actionable insights
# Trader Behavior vs Market Sentiment Analysis

## Overview
This project analyzes how cryptocurrency trader performance and behavior vary across different market sentiment regimes (Fear, Greed, Extreme Greed, Neutral). Using historical trader-level data and the Bitcoin Fear & Greed Index, the analysis explores performance metrics, behavioral patterns, and trader segmentation. A simple predictive model is included as an optional extension.

---

## Dataset
- **Trader Data**: Historical trade-level data containing execution prices, trade size, direction, and PnL.
- **Market Sentiment Data**: Daily Bitcoin Fear & Greed Index values.

Both datasets are aligned at a daily level for analysis.

---

## Methodology
1. **Data Preparation**
   - Cleaned and aligned trader and sentiment datasets by date.
   - Engineered daily metrics such as PnL, trade count, win rate, and sentiment labels.

2. **Exploratory Analysis**
   - Compared average PnL across sentiment regimes.
   - Analyzed changes in trade frequency based on sentiment.
   - Segmented traders into high vs low win-rate and high vs low frequency groups.

3. **Segmentation Analysis**
   - Evaluated how different trader segments perform under varying sentiment conditions.

4. **Bonus: Predictive Modeling (Optional)**
   - Built a simple logistic regression model to predict next-day trader profitability using sentiment and behavioral features.

---

## Key Insights
- Trader performance differs significantly by sentiment, with **Fear days showing the highest average PnL**.
- Traders increase trade frequency during Fear-driven markets, indicating heightened activity during volatility.
- High win-rate traders perform consistently across all sentiment regimes, while low win-rate traders tend to underperform during Greed and Extreme Greed phases.
- High-frequency trading strategies outperform during Fear and Greed, whereas low-frequency strategies are more effective during Neutral market conditions.

---

## Actionable Strategy Recommendations
- **Selective Aggressiveness During Fear**: High win-rate or high-frequency traders can increase participation during Fear-driven markets, while low win-rate traders should reduce exposure to manage risk.
- **Risk Control During Greed and Extreme Greed**: Low win-rate and low-frequency traders should apply stricter trade filters and reduce leverage during Greed phases to avoid losses driven by overconfidence.

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/eshikasinghania07/trader-sentiment-analysis


