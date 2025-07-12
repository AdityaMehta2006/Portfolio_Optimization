# 📊 Portfolio Optimization using Modern Portfolio Theory

This project implements a complete portfolio optimization workflow using Modern Portfolio Theory (MPT). It aims to construct an optimal portfolio of selected assets that maximizes the Sharpe ratio under standard constraints (no shorting, weights sum to 1).

The project is designed to reflect skills relevant to quantitative research and trading roles.

---

## 🧠 Key Concepts

- **Modern Portfolio Theory (MPT)**
- **Mean-Variance Optimization**
- **Sharpe and Sortino Ratios**
- **Efficient Frontier Visualization**
- **CAPM Regression vs S&P 500**
- **Monte Carlo Simulation**
- **Principal Component Analysis (PCA)**

---

## 📁 Project Structure

| Section | Description |
|---------|-------------|
| `1. Introduction` | Problem statement and financial context |
| `2. Data Acquisition` | Daily price data via Yahoo Finance |
| `3. Return & Risk Metrics` | Log returns, annualized stats |
| `4. Optimization` | Max Sharpe portfolio using `scipy.optimize` |
| `5. Efficient Frontier` | Visualization of random portfolios |
| `6. Portfolio Metrics` | Sharpe, Sortino, Max Drawdown |
| `7. Monte Carlo Simulation` | Simulates 1-year portfolio paths |
| `8. PCA Risk Analysis` | Diversification check using PCA |
| `9. CAPM vs Benchmark` | Alpha and beta estimation against S&P 500 |
| `10. Export Results` | Save weights/outputs for further analysis |

---

## 🚀 Technologies Used

- Python 3
- `numpy`, `pandas`, `matplotlib`
- `yfinance` for market data
- `scipy.optimize` for constrained optimization
- `statsmodels` for CAPM analysis
- `sklearn` for PCA

---

## 📈 Sample Outputs

![Efficient Frontier](assets/efficient_frontier.png)
*Efficient Frontier with optimal Sharpe portfolio (gold star)*

---

## ✅ Output Metrics (Example)

- **Expected Annual Return**: ~21.3%
- **Annual Volatility**: ~18.2%
- **Sharpe Ratio**: ~1.12
- **Sortino Ratio**: ~1.42
- **Max Drawdown**: ~-11.4%

---

## 📤 How to Use

1. Clone this repository:
