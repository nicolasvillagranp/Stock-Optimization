# Optimization of an Investment Portfolio

## Project Overview
This project aims to design the best possible investment strategy for a set of financial assets. The approach balances maximizing returns with minimizing risk, using a combination of forecasting and optimization techniques.

## Key Components
1. **Forecasting:**  
   - **Price Estimation:** Uses ARIMA models and LSTM neural networks to predict stock prices.  
   - **Risk Estimation:** Implements GARCH models to estimate market volatility.  

2. **Optimization Model:**  
   - Uses **Mixed-Integer Linear Programming (MILP)** to incorporate expert-driven constraints and market insights.  
   - Constructs an optimal investment portfolio under constraints such as risk limits and sector diversification.  
   - Based on principles from Markowitz's Portfolio Theory.  
   - Uses linear programming to maximize expected returns while controlling risk.

## Implementation Details
- **Programming Language:** Python  
- **Libraries Used:** TensorFlow, SciPy, Pandas, NumPy, PuLP (for MILP)  
- **Input Data:** Historical stock prices, expert-driven risk parameters, and investment constraints.  
- **Output:** Optimal investment strategy stored in a CSV file.

## Results
- The model achieved a **37.5% theoretical ROI**, though real-world execution yielded a **5% ROI in five days**.
- The use of **MILP allows for integrating expert knowledge** into the model, ensuring the portfolio remains aligned with real-world financial strategies.
- The optimization constraints proved effective in maintaining a balanced trade-off between risk and return.

## How to Run the Project
1. Install required dependencies:
   ```bash
   pip install numpy pandas scipy tensorflow pulp

