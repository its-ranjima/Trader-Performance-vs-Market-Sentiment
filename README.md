# Trader-Performance-vs-Market-Sentiment
Trader Performance vs Market Sentiment analysis on Hyperliquid data. Includes daily metrics, Fear vs Greed comparisons, trader segmentation, visualizations, and actionable strategy recommendations.
Contents

Trader_Performance_vs_Market_Sentiment.ipynb: Full notebook with all code, subtitles, analysis, and visualizations.

# Methodology

- Loaded Bitcoin Market Sentiment and Historical Trader Data.

- Cleaned datasets, handled missing values, and converted timestamps to dates.

- Calculated daily metrics per trader: PnL, win rate, average trade size, leverage, trades per day, long/short ratio.

- Merged trader data with sentiment data and analyzed:

- Differences in PnL and win rate on Fear vs Greed days

- Changes in trading behavior (trade frequency, leverage, long/short bias)

- Segmented traders into:

- High vs Low leverage

Frequent vs Infrequent

- Consistent vs Inconsistent winners

- Key Insights

- PnL tends to decrease on Fear days for high-leverage traders.

- Frequent traders increase trade activity on Greed days.

- Long/Short trade bias shifts based on market sentiment.

- Strategy Recommendations

- Reduce leverage for high-leverage traders during Fear days.

- Increase trade frequency only for consistent traders during Greed days.
