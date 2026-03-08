# Trader_Behaviour_Sentiment_Analysis
Analyzing Hyperliquid trader performance against Bitcoin Fear &amp; Greed Index to uncover behavioral patterns and sentiment-driven trading strategies
Trader Performance vs. Market Sentiment Analysis 📊

​🎯 Project Objective: 

​The goal of this project is to analyze the relationship between Bitcoin Market Sentiment (Fear & Greed Index) and the trading performance/behavior of users on the Hyperliquid platform. By aligning these datasets, we aim to uncover patterns that can inform risk-adjusted trading strategies.
​📂 Repository Structure
​notebooks/jd_5.ipynb: Complete data cleaning, merging, and exploratory data analysis (EDA).
​requirements.txt: List of Python libraries required to run the analysis.
​README.md: Project summary and key findings.
​🔍 Key Insights & Findings
​1. Profitability vs. Sentiment
​Peak Performance: The highest average profitability ($205.81) occurs during 'Extreme Greed' phases, where traders successfully ride market trends.
​The Struggle in Fear: During 'Extreme Fear', average profit drops significantly to just $1.89, indicating high capital erosion.
​2. The Volatility Anomaly (Outlier Analysis)
​Fear (Green) Zone: My analysis of the PnL distribution (Boxplots) revealed that the 'Fear' (Green) category contains the highest number of outliers. This suggests that while average profits are low, the market is highly unpredictable with extreme swings.
​Extreme Fear (Red) Zone: Interestingly, this zone shows the fewest outliers, indicating a "dead" or consistently stagnant market where big "win" surprises are rare.
​3. Behavioral Shifts
​Over-trading in Panic: Traders exhibit higher trade frequency during 'Extreme Fear', likely due to revenge trading or panic-driven decisions.
​Strategic Bias: During 'Extreme Greed', the Long/Short ratio drops (to approx 0.41), suggesting that experienced traders start positioning for reversals.
​💡 Strategy Recommendations (Rules of Thumb)
​Based on the data, I propose the following rules:
​Rule 1 (The Volatility Buffer): During Fear (Green) days, reduce position size by 50%. The high frequency of outliers makes this a high-risk environment where capital protection is priority.
​Rule 2 (The Efficiency Filter): During Extreme Fear (Red) days, minimize trading frequency. Since there are very few positive outliers, the probability of a "jackpot" trade is extremely low.
