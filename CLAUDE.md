# Linear Regression - Fund Analysis

## Project Overview

Data preprocessing and supervised learning project for analyzing investment funds using linear regression models (Fama-French factors, industry factors, and individual assets).

## Financial Thesis

As portfolio managers, we believe the Asian market will perform well next year; therefore, we aim to position our fund of funds with a clear bias toward this market.

## Dataset

- **NAVs**: Net Asset Values of 25,000 investment funds (2016-01-05 to 2021-07-16), provided by IronIA (`data/navs.pickle`).
- **Fama & French factors**: Mkt-RF, SMB, HML, MOM for Asia Pacific ex Japan (`data/factores_unificados.csv`).

## Project Structure

- `src/eda_pickle.ipynb` — Exploratory data analysis and preprocessing of the NAVs pickle dataset.
- `src/APT_fondo_solucion.ipynb` — OLS regression analysis of a fund using Fama-French 3-factor model, industry factors, and individual stock returns.
- `doc/` — Project instructions and documentation.
- `data/` — Raw data files (not tracked in git).

## Key Libraries

numpy, pandas, statsmodels, yfinance, matplotlib

## Conventions

- Language: Spanish (comments and markdown), English (code variables and library usage).
- Notebooks are the primary working format.
- Returns are computed as log-returns or percentage changes depending on context.
