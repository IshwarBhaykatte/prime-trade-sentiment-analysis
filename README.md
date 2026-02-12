# prime-trade-sentiment-analysis


📊 Trader Behavior vs Market Sentiment Analysis
📌 Objective

This project analyzes how trader performance changes under different market sentiment conditions (Fear vs Greed Index). The goal is to identify behavioral patterns and design data-driven trading strategies.


⚙️ Methodology
1.Cleaned and processed historical trading data
2.Merged with Fear & Greed sentiment index
3.Created performance metrics:
>Profit/Loss (PnL)
>Win Rate
>Trade Size
>Volatility (Risk)

4.Grouped performance by sentiment classification:
>Extreme Fear
>Fear
>Neutral
>Greed
>Extreme Greed

📈 Key Insights

Extreme Greed shows the highest average profit and win rate
Traders take largest risks during Fear, but performance is unstable
Extreme Fear has the highest volatility, indicating panic trading
Neutral markets provide the most stable but lower returns

| Sentiment     | Strategy                                     |
| ------------- | -------------------------------------------- |
| Extreme Greed | Increase position size (higher success rate) |
| Fear          | Reduce position size (high volatility)       |
| Extreme Fear  | Avoid aggressive trading (panic behavior)    |
| Neutral       | Use low-risk strategies                      |


🛠 How to Run

1.Clone the repository
2.Install dependencies:
  pip install pandas matplotlib seaborn
3.Open the Jupyter notebook and run all cells


📂 Output Visualizations

Graphs included in this repository show:
Mean PnL by Sentiment
Win Rate by Sentiment
Volatility by Sentiment
Average Position Size


