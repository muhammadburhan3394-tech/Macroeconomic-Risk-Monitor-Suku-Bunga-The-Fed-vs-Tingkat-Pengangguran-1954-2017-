# Macroeconomic Risk Monitor: Interest Rates vs. Unemployment (1954-2017)

**Explore the Interactive Tableau Dashboard here:** [INSERT YOUR TABLEAU PUBLIC LINK HERE]

## Project Overview
In the banking and financial sector, keeping an eye on macroeconomic indicators like the Federal Funds Rate and Unemployment is crucial. These indicators help institutions anticipate shifts in the market, manage loan default risk, and adjust credit strategies accordingly. 

This project explores 60 years of US economic data to understand how central bank monetary policies impact the labor market, and what those shifts mean for financial institutions.

## The Data
The dataset contains historical US macroeconomic indicators from 1954 to 2017, including:
* **Monetary Policy:** Effective Federal Funds Rate, Target Rates.
* **Economic Health:** Unemployment Rate, Inflation Rate, Real GDP.

## Tools & Methods
* **Python (Pandas, Matplotlib):** Used for Exploratory Data Analysis (EDA) and data cleaning. Handled mismatched reporting frequencies (monthly vs. quarterly data) using the `Forward Fill` method to preserve the integrity of the time-series data.
* **Tableau:** Built an interactive Dual-Axis dashboard to precisely compare two metrics with different scales (percentages).

## Key Findings
1. **The Crisis Cycle:** Visual analysis shows a strong inverse relationship during economic shocks (e.g., the 2008 Financial Crisis). Unemployment spikes drastically just as the central bank slashes interest rates to near 0% to save market liquidity.
2. **The Lag Effect:** A simple statistical correlation test showed a weak linear relationship (~0.09). However, visual EDA proved that this is due to the "lag effect" of economic policies—confirming that looking at raw statistics without visual context can be misleading.

*(Optional: Insert a screenshot of your Tableau Dual-Axis dashboard here)*

## Business Recommendations
1. **Proactive Credit Scoring:** When the central bank enters an aggressive rate-hiking phase, risk departments should tighten commercial loan approval criteria before the economic slowdown hits the labor market.
2. **Optimizing Liquidity:** When rates are slashed drastically in response to a crisis, banks should focus on credit restructuring for existing borrowers while shifting liquidity into high-quality fixed-income assets to protect margins.

---
*This project is part of my data analysis portfolio. If you have any questions or want to discuss financial data analysis, let's connect on [INSERT YOUR LINKEDIN PROFILE LINK HERE].*
