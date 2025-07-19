# Stochastic-Portfolio-Project
# 📈 Stochastic Modeling for Financial Risk Management

This project applies stochastic modeling techniques to simulate, analyze, and evaluate risk in financial markets. It explores the behavior of asset returns using theoretical models and real-world data — combining statistical analysis with simulation-based methods for portfolio and risk modeling.

## 🧠 Key Concepts Covered

- **Geometric Brownian Motion (GBM)** for asset price simulation
- **Fat-tailed distributions** (Student-t) to model real-world return behavior
- **Historical, parametric (normal), and Student-t Value at Risk (VaR)**
- **Rolling volatility estimation** and time-dependent risk
- **Model backtesting** using hit rate and MSE
- **Multi-asset portfolio simulation** with asset allocation
- **Model fit evaluation** using:
  - Q-Q plots
  - AIC / BIC
  - Kolmogorov-Smirnov test

---

## 🗂 Project Structure

```plaintext
stochastic-modeling/
│
├── notebooks/
│   └── Stochastic Modelling Project.ipynb   # Main notebook
│
├── plots/                                   # Saved figures (VaR, rolling vol, etc.)
├── report/                                  # (Optional) Final write-up or summary
├── src/                                     # (Optional) Helper Python scripts
├── requirements.txt                         # Python dependencies
└── .gitignore                               # Ignore system files and checkpoints
