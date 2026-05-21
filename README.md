# Automated-Investor-PowerBI-Dashboard

# 📊 Automated Investor Power BI Dashboard

## 🚀 Overview

Automated Investor Power BI Dashboard is an AI-powered financial analytics and visualization platform that combines:

- Real-time stock market data
- Technical indicators
- Large Language Models (LLMs)
- Fundamental analysis
- Interactive Power BI dashboards

The project automates financial intelligence extraction from annual reports and synthesizes it with live market signals to generate actionable investment insights.

---

# 🎯 Problem Statement

Equity research teams face information overload while analyzing:

- Annual reports
- ESG filings
- Financial statements
- Market volatility
- Trading signals

This project bridges the gap between:

✅ Quantitative Market Data  
✅ Fundamental Financial Analysis  
✅ AI-driven Insight Extraction

---

# 🧠 Key Features

- 📈 Real-time stock market ingestion using `yfinance`
- 🤖 Gemini LLM integration for annual report analysis
- 📊 Power BI dashboard visualization
- 📉 Technical indicators:
  - RSI
  - MACD
  - SMA
  - Volume Analysis
- 🧾 Automated extraction of financial metrics from PDFs
- 🧠 Sentiment and signal intelligence engine
- ⭐ Star-schema data warehouse modeling
- ⚡ CSV-based caching layer
- 📂 Unified analytics pipeline

---

# 🏗️ System Architecture

## Path A — Quantitative Pipeline

```text
yfinance API
    ↓
OHLCV Data
    ↓
Technical Indicators
    ↓
Fact_Technicals.csv

```text


