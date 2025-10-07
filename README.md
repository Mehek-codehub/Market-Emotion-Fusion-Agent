# Market-Emotion-Fusion-Agent
AI agent fusing market volatility + news sentiment for actionable insights
# Market Volatility & Emotion Fusion Agent

## 🚀 Project Overview
This project builds an **AI agent** that fuses **market volatility data** with **financial news sentiment** to generate actionable insights for investors.

- Analyzes **stock price volatility** (5-day rolling) using `yfinance`.
- Fetches **news headlines** and computes **sentiment/emotion scores** using FinBERT.
- Fuses volatility and negative sentiment to calculate a **Market Fear Score**.
- Generates **plain-English market insights** (optional GPT-powered).

## 🧩 Features
- Real-time market volatility analysis
- Financial news emotion scoring
- Fused market risk score
- Optional AI-generated market report

## ⚙️ Tech Stack
- Python 3.x
- yfinance
- pandas, numpy, matplotlib
- Transformers (FinBERT)
- OpenAI GPT (optional)
- BeautifulSoup for news scraping

## 📈 Sample Output
Market Emotion Score: {'Positive': 0.25, 'Neutral': 0.40, 'Negative': 0.35}
Fused Market Fear Score: 0.62
Market Insight Report: "High market fear detected in AAPL due to rising volatility and negative news sentiment. Investors should monitor short-term risk."


## 💻 How to Run
1. Clone the repository:
```bash
git clone https://github.com/Mehek-codehub/Market-Emotion-Fusion-Agent.git
cd Market-Emotion-Fusion-Agent
