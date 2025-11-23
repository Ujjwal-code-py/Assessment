# Trader Performance vs Market Sentiment – Ujjwal Gupta

## Project Overview  
This analysis explores the relationship between trader performance (from Hyperliquid) and market sentiment (Bitcoin Fear & Greed Index). The objective is to uncover hidden patterns and provide actionable insights to build smarter crypto trading strategies.

## Datasets Used  
- **Historical Trader Data** – from Hyperliquid: includes account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.  
- **Market Sentiment Index** – Bitcoin Fear & Greed Index: columns include Date and Classification (Fear/Greed/Extreme Fear/Extreme Greed/Neutral).

## Folder Structure  



## How to Run  
1. Open the notebook via the following Colab link.  
2. Upload both CSV files when prompted.  
3. Run all cells to reproduce the analysis and visualizations.

### Google Colab Link  
[Open in Colab](https://colab.research.google.com/drive/1Bz-nYu6zlD0XtlCdFp5b3LMh3wE1eWre?usp=sharing)

## Key Findings  
- Traders perform **best** during *Greed / Extreme Greed* sentiment regimes — higher average PnL and win-rate.  
- Performance falls during *Extreme Fear* days — lowest win-rate and lowest profitability.  
- Traders increase position size during high-emotion market regimes (Greed & Fear).  
- During *Extreme Greed*, traders shift toward profit-taking and shorting.  
- A higher share of accounts are profitable during Greed / Extreme Greed compared to Neutral or Extreme Fear.

## Strategy Recommendations  
- **Increase risk exposure and trade frequency** during Greed/Extreme Greed days — favorable regime for performance.  
- **Reduce exposure or pause trading** during Extreme Fear days — high risk/low reward regime.  
- Employ **sentiment-aware rules**: adjust position size, direction bias (buy vs sell) and leverage based on sentiment.  
- Beginners may trade only in Greed regimes; advanced traders may build reversal strategies for Extreme Fear with strict risk controls.

## Author  
Ujjwal Gupta  
BTech in Information Technology  

---

