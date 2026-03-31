# Global Multi-Asset Portfolio with Risk-Adjusted Strategy (Created using Excel)
## Description
This project presents an attempt in the construction and analysis of a global multi-asset portfolio over a 5 year horizon (2020–2025), combining equities, ETFs, and REITs.

The objective is to design a portfolio that balances return and risk while outperforming its benchmark (MSCI World), through disciplined asset allocation and risk management for a risk adverse investor.

## PROJECT
- <a  href= " https://github.com/louna-mengue/Investment-Portfolio-Performance-using-Excel/blob/main/PORTFOLIO%20PERFORMANCE%201%20(version%201).xlsb" > excel project </a>
https://1drv.ms/x/c/f20ea053dcd68fb5/IQCO3PJPKnwhRLEwpZ-wghqaAbRVdRH_hifnR_i0ym-MjW8?e=IbBljU

## Data Collection & Processing
Stock prices manually extracted from Investing.com 
Monthly frequency applied to reduce noise
Data cleaned and aligned across assets
Missing values handled via forward fill
Returns computed using log returns

Market data used in this project was sourced from Investing.com and covers the period from January 2020 to December 2025.
The dataset includes monthly prices for all selected assets (DIS, GOOGL,CNYA, etc).
Raw datasets are available in the folder for reproducibility.

## METHODOLOGY
The portfolio was built using a structured buy-side approach:

1. Asset Selection

Selection of global equities and ETFs across the US, Asia, and UK
Inclusion of REIT exposure for diversification

2. Portfolio Construction

Allocation based on expected return, volatility, and correlations
Optimization inspired by a mean-variance framework

3. Data & Assumptions

Monthly data over a 5-year horizon (2020–2025)
Stable correlations and macroeconomic environment assumptions

4. Performance Analysis

Comparison vs MSCI World benchmark
Evaluation of risk-adjusted performance

5. Risk Analysis

Drawdown analysis
Stress testing:
Market shocks (-20%, -30%)
Interest rate shock (+100bps)

6. Monitoring

Portfolio tracking via dashboard (performance, allocation, risk metrics)

## DASHBOARD INTERACTION
- <a href= "https://github.com/louna-mengue/Investment-Portfolio-Performance-using-Excel/blob/main/Capture%20d%E2%80%99%C3%A9cran%20Portfolio%20Dashboard.png" > Portfolio Dashboard</a>

<img width="960" height="427" alt="Capture d’écran Portfolio Dashboard" src="https://github.com/user-attachments/assets/f4ec3335-84d5-4ea5-9577-ce6c701397f7" />


## INVESTMENT QUESTIONS (KPI's)
What is the return?
What level of risk is taken to achieve this return?
Is the portfolio efficiently compensated for risk?
Does the portfolio outperform its benchmark?
How sensitive is the portfolio to market movements?
What is the downside risk?
Does the portfolio protect capital during downturns?
What drives performance?
Is the portfolio well diversified?

## KEY RESULTS
Outperformance vs MSCI World (relative performance: 1.12)
Strong risk-adjusted returns (Sharpe Ratio: 0.51)
Defensive positioning (beta < 1)
Resilience during market downturns (stress-tested scenarios)
Positive alpha generation (+1.45%)

## LIMITATIONS
Geographic concentration (US and Asia exposure)
Stable correlation assumption (not really realistic during crises)
No macroeconomic or monetary regime shifts considered


## CONCLUSION

This project highlights that performance is not only driven by asset selection, but by disciplined allocation and risk management.

It also shows that a portfolio can outperform while maintaining a defensive profile, although achieving true diversification remain the main challenge for a beginner.
