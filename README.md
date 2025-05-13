# 📊 Financial Risk Analysis of Lockheed Martin (LMT) Using Time Series Models

## 🗂 Project Overview

This project performs a financial time series analysis of **Lockheed Martin (LMT)** stock data using models such as **ARCH** and **GARCH**. The focus is on **volatility modeling**, **Value at Risk (VaR)**, and **Expected Shortfall (ES)** to quantify and interpret downside financial risk over a 10-year historical period (2014–2024). Data is retrieved using the `yfinance` API.

---

## 🎯 Objectives

- Analyze the historical stock prices of Lockheed Martin over a decade.
- Apply time series modeling (ARCH/GARCH) to understand volatility dynamics.
- Quantify investment risk through statistical metrics like VaR and ES.
- Assess the impact of geopolitical events on stock volatility.

---

## 🛠️ Technologies & Tools Used

| Tool / Library        | Purpose                                           |
|-----------------------|---------------------------------------------------|
| `Python`              | Core programming language                         |
| `pandas`, `numpy`     | Data manipulation and numerical computation       |
| `matplotlib`          | Data visualization                                |
| `yfinance`            | Accessing historical stock price data from Yahoo  |
| `arch` (Python lib)   | Volatility modeling (ARCH/GARCH)                  |
| `scipy.stats`         | Statistical calculations (e.g., normal VaR/ES)    |

---

## 💡 Project Highlights

### 🔍 1. Dataset Overview

- **Ticker**: Lockheed Martin Corporation (LMT)
- **Time Range**: 2014 to 2024
- **Fields**:
  - Price data: Open, High, Low, Close, Adjusted Close
  - Returns: Log returns for stationarity
  - Volatility metrics: GARCH-based conditional volatility
  - Risk metrics: Value at Risk (VaR) and Expected Shortfall (ES)

### 🌍 2. Contextual Relevance

Lockheed Martin, as a global defense contractor, shows volatility patterns closely tied to geopolitical events:

- COVID-19 market crash
- Russia–Ukraine war
- Israel–Palestine escalation
- Global defense spending surges

These periods offer practical insights into how geopolitical tensions influence financial risk in defense stocks.

### 📉 3. Time Series Modeling

- Applied **ARCH** and **GARCH(1,1)** models to forecast conditional volatility.
- Visualized volatility clustering and persistence.
- Evaluated models using AIC and residual diagnostics.

### 🧮 4. Risk Estimation

- **Value at Risk (VaR)** computed at 95% and 99% confidence levels.
- **Expected Shortfall (ES)** calculated to capture tail risk beyond VaR.
- Results help in quantifying potential extreme losses for investors and funds.

---

## 📈 Insights

- LMT exhibits **volatility clustering** typical of financial time series.
- **ARCH/GARCH** models effectively capture risk spikes around global events.
- **VaR and ES** provide actionable risk thresholds for portfolio management.
- Defense stocks react strongly to real-world tensions—valuable for risk-sensitive investing.

---

## 👨‍💼 Use Cases

- **Investors**: Adjust portfolios based on predicted risk under stress scenarios.
- **Risk Analysts**: Use GARCH models to measure time-varying volatility.
- **Academics**: Explore the impact of political events on defense sector risk.

---
