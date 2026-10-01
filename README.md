<h1 align="center">Matthew Hermosura</h1>

<p align="center">
  Data Science + Applied Mathematics at UT Dallas &middot; data pipelines and machine learning for finance and alternative data
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/matthew-hermosura"><img alt="LinkedIn: matthew-hermosura" src="https://img.shields.io/badge/LinkedIn-matthew--hermosura-0A66C2"></a>
  <a href="mailto:matthewhermosura@gmail.com"><img alt="Email: matthewhermosura@gmail.com" src="https://img.shields.io/badge/Email-matthewhermosura%40gmail.com-D14836?logo=gmail&logoColor=white"></a>
</p>

I'm a double major in Data Science and Applied Mathematics (GPA 4.0, graduating December 2027). I like problems where
the data is messy and the answer has to hold up against reality: forecasting, alternative data, and evaluation that is
honest about what a model cannot see. I'm looking for **Summer 2027 data science and machine learning internships**.

## Featured: PanelCast

**[PanelCast](https://github.com/HermosuraM/panelcast)** is an alternative-data revenue nowcasting lakehouse. A PySpark
and Delta Lake pipeline ingests ~19M simulated card transactions from five data vendors, anchored to real SEC EDGAR
revenue; resolves messy merchant strings to tickers; detects vendor data failures; corrects panel bias with daily
census raking; and forecasts quarterly revenue for 20 public companies about four weeks before they report. A
LangGraph agent turns the results into pre-earnings notes whose every number is checked against the data.

| Measured | Result |
|---|---|
| Revenue nowcast error, ensemble vs. naive baseline | **2.1 pp** vs. 6.3 pp mean absolute error |
| Merchant entity resolution vs. ground truth | **100% precision**, 98% recall |
| Injected vendor data failures detected | **13 of 13**, 0 false positives |
| Panel growth error, raw spend to fully corrected | 28.7 pp to **1.9 pp** |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HermosuraM/panelcast/main/reports/figures/nowcast_timeseries_dark.png">
  <img alt="Reported revenue growth versus PanelCast nowcasts for Walmart, Starbucks and Uber, 2020 to 2026" src="https://raw.githubusercontent.com/HermosuraM/panelcast/main/reports/figures/nowcast_timeseries_light.png">
</picture>

`PySpark` `Delta Lake` `Databricks` `Spark SQL` `scikit-learn` `LangGraph` `Claude API` `pytest` `GitHub Actions`

## More work

| Project | What it is | Stack |
|---|---|---|
| **Financial Opportunity Copilot** (2026) | ML pipeline that flags six financial-wellbeing opportunities across 41K+ customers (0.94-1.00 PR-AUC), plus a Claude tool-calling agent that grounds every dollar figure in deterministic finance functions | Python, scikit-learn, SQLite, Claude API |
| **Regime-aware market forecasting** (ACM Research, 2026) | Gaussian HMM regimes with a bidirectional LSTM and multi-head attention over a 73-ticker portfolio; 58.1% directional accuracy and a 2.00 Sharpe ratio on SPY under walk-forward validation | PyTorch |
| [Seoul bike demand regression](https://github.com/HermosuraM/Seoul_Bike_Sharing_Regression) | Regression models for hourly bike-rental demand on the UCI Seoul Bike Sharing dataset | Python |
| [SpendWise](https://github.com/HermosuraM/spendwise) ([live demo](https://hermosuram.github.io/spendwise/)) | Local-first budgeting app with explainable insights: recurring-charge detection, robust (median/MAD) anomaly flags, and a month-end forecast that blends this month's pace with a three-month baseline; 66 tests, deployed by GitHub Actions | React, Vite, Supabase, Recharts, Vitest |
| [Retail inventory and analytics](https://github.com/HermosuraM/CS4347_project) | Inventory and analytics web app built for a database systems course | PHP, MySQL |

## Toolbox

- **Languages:** Python, SQL, R
- **Data engineering:** PySpark, Spark SQL, Delta Lake, Databricks, pandas, NumPy
- **ML and statistics:** scikit-learn, PyTorch, statsmodels, time-series analysis, Bayesian methods, hypothesis testing
- **LLM systems:** LangGraph, LangChain, Claude API, tool calling, structured outputs
- **Engineering:** Git, GitHub Actions, pytest, Docker

## Experience

- **Product Management Intern**, Solera Holdings (Jun-Jul 2026): requirements for a probabilistic scoring model in the AutoSource vehicle-valuation stack
- **Undergraduate Researcher**, ACM Research, UT Dallas (Jan-May 2026): regime-aware market forecasting (above)
- **Undergraduate Researcher**, Texas Biomedical Device Center (Feb-May 2025): EMG motor-unit decomposition across 50 experimental trials
- **Events Officer**, Data Science Club, UT Dallas (2026-present)
