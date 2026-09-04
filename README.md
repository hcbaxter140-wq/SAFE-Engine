# SAFE (Sector Adaptive Fundamental Engine)

## Overview:
S.A.F.E. is a Python and Excel-based equity screener I've created to automate my static financial analysis on companies

As a Finance undergrad, minoring in Economics, my priority is to spend my time manually scanning 10-Ks and mapping out 3-statment cash flow models. 
While my time is spent reading over 10-Ks and refining my skills, I have engineered S.A.F.E. to automatically scrape the same equations I use so that I can analyze companies in a shorter amount of time.

**ROIC vs. WACC:** The core of my engine screens for companies who generate a positive Return on Invested Capital spread against an estimated cost of capital (EVA).
**Data Cleaning:** My system utilizes Z-Scores to flag and clean equity outliers or accounting distortions in the financial statements.
**Valuation:** S.A.F.E. has been created to automate base-level Discounted Cash Flow (DCF) models, using basic Monte Carlo simulations to test various revenue and margin growth scenarios.
**Risk Assessment:** Utilizes Kelly Criterion concepts to flag position sizing based on estimated alpha and it's historical variance.

**Languages:** Python (Pandas, NumPy, SciPy)
**Ingestion:** Google Apps Scripts, Jupyter Notebook, Visual Studio Code, yfinance
**Outputs:** Excel Workbooks (openpyxl) and DCF model generation

## Current Learning Roadmap
This is an active student project. While this system automates distinct financial metrics and base-level DCF simulations, I strictly use its outputs as a starting point. Any company whihch is flagged by the code is still manually torn down and verified before being considered a good investment decision.

The roadmap that I've created and am following involves refining the mathematical models within the engine as I progress through asset pricing and advanced economic theory in my degree.
