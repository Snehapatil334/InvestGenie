
# 💰 InvestGenie - AI-Powered Portfolio Optimizer

**InvestGenie** is a powerful and intelligent investment assistant that helps users build personalized portfolios based on their financial goals, risk preferences, and market conditions. Built with Streamlit and enhanced with GenAI capabilities, this tool enables smarter investment decisions through real-time data, sentiment analysis, and AI-generated insights.

---

## 🚀 Features

- 📊 User-defined investment preferences (amount, risk tolerance, term, and crypto preference)
- 💹 Automated asset allocation across stocks, bonds, ETFs, and alternatives
- 📈 Historical return and volatility analysis using Yahoo Finance data
- 🤖 Market sentiment analysis powered by **FinBERT**
- 🧠 Natural language portfolio insights using **DistilBERT QA model**
- 🎯 Risk-adjusted metrics (Sharpe ratio, expected return, volatility)
- 🧩 Interactive visual summaries using **Plotly** and **Streamlit UI**

---

## 🛠️ Tech Stack

- **Language**: Python
- **Framework**: Streamlit
- **ML/NLP Models**: FinBERT, DistilBERT (Transformers)
- **APIs & Libraries**: yfinance, pandas, NumPy, Plotly, Transformers, Matplotlib, Torch

---

## 📦 Setup Instructions

1. **Clone the repo**:
```bash
git clone https://github.com/your-username/investgenie.git
cd investgenie
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Run the app**:
```bash
streamlit run investgenie_app_final.py
```

---

## 🧠 AI Capabilities

- **Sentiment Analysis**: Uses FinBERT to gauge market sentiment based on asset-related news.
- **Q&A Engine**: Uses DistilBERT to answer questions about portfolio performance, risk, and optimization strategies.

---

## 📊 Output

- Detailed tables of asset allocation with expected return and volatility
- Pie chart of asset class distribution
- Interactive portfolio insights and recommendations

---

## 📌 Disclaimer

This project is for educational and informational purposes only. The portfolio suggestions are based on historical data and basic financial heuristics. It is not intended to replace professional financial advice.

