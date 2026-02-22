# Data-science-trading-analysis
ata-driven analysis of trader performance across Fear &amp; Greed market regimes using behavioral metrics and sentiment-based segmentation.
Trader Performance vs Market Sentiment Analysis
Objective

This project analyzes how trader performance and behavior change across different market sentiment regimes, specifically Fear and Greed conditions.

The goal is to understand whether traders adapt their behavior to market sentiment and how profitability varies across these regimes.

Datasets

Historical trader transaction data

Fear & Greed Index data

Methodology
1. Data Preparation

Loaded and inspected both datasets

Converted timestamps into daily format

Aggregated trade data at a daily and trader level

Merged daily sentiment classification with trading activity

Validated data for missing values and duplicates

2. Metrics Created

For each trader on a daily basis, the following metrics were computed:

Daily PnL

Win rate

Trade frequency

Average trade size

Long/Short ratio

Trader segmentation (High-frequency vs Low-frequency traders)

3. Analysis Approach

Compared performance across different sentiment regimes

Evaluated behavioral shifts in trading activity

Segmented traders based on activity levels to identify differences in regime sensitivity

Key Insights
1. Fear Days Show the Strongest Performance

Fear regimes recorded:

The highest average daily PnL

Higher win rates

Increased trading activity

This suggests that volatility during fearful market conditions creates more trading opportunities, which active traders are able to exploit effectively.

2. Extreme Greed Reduces Trading Edge

During Extreme Greed regimes:

Win rates declined

Average profitability dropped

Trading behavior suggested overconfidence and late trend participation

This indicates that euphoric market conditions may reduce risk-reward quality and increase crowding.

3. High-Frequency Traders Benefit Most From Volatility

High-frequency traders demonstrated:

Strongest performance during Fear regimes

Significantly higher PnL compared to low-frequency traders

Low-frequency traders displayed more stable but lower returns, with less sensitivity to sentiment shifts.

Strategy Recommendations
Rule 1: Increase Participation During Fear

High-frequency traders can consider increasing participation during Fear regimes, as volatility appears to enhance opportunity.

Rule 2: Reduce Risk During Extreme Greed

During Extreme Greed phases, reducing trade size and frequency may help preserve capital, as trading edge appears to decline in highly euphoric markets.

Conclusion

The analysis highlights that market sentiment significantly impacts both trader behavior and performance. Traders who adjust participation levels based on sentiment regimes may improve risk-adjusted outcomes.
