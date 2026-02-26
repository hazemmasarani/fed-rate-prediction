# Fed Rate Prediction

## Project
This project analyzes macroeconomic and financial indicators to predict changes in the US Federal Funds Rate. 
We aim to identify the most significant variables, create meaningful categorical features, and explore modeling approaches such as regression and clustering to gain actionable insights.

## Objective
- Explore macroeconomic and financial variables from FRED.
- Derive categorical variables such as Hike/Cut/Hold for interest rate changes and inflation regimes.
- Identify the most significant predictors of Fed Funds Rate changes.
- Compare models using BIC and cross-validation to select the best-performing approach.
- Apply clustering to analyze patterns in economic conditions and interest rate behavior.

## Dataset
- Source: [FRED (Federal Reserve Economic Data)](https://fred.stlouisfed.org)
- Contains macroeconomic and financial indicators such as GDP, inflation, unemployment, and more.
- Includes both continuous variables and derived categorical features.

## Project Structure
fed-rate-prediction/
├── data/ # Raw and processed datasets
├── data_acquisition/ # Scripts to download and process data
├── preprocessing/ # Data cleaning & feature engineering
├── eda/ # Exploratory Data Analysis (plots, summaries)
├── features/ # Derived categorical variables
├── models/ # Regression, stepwise, clustering scripts
├── results/ # Model outputs, plots, BIC scores, tables
└── README.md # Project overview and instructions

## Setup
1. Clone the repository: git clone https://github.com/yourusername/fed-rate-prediction.git
2. Run scripts in order: `data_acquisition/` → `preprocessing/` → `eda/` → `features/` → `models/`

## References
- FRED Database: https://fred.stlouisfed.org
