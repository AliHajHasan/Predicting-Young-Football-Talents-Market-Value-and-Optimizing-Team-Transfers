# Predicting-Young-Football-Talents-Market-Value-and-Optimizing-Team-Transfers
## Project Overview

This thesis presents a data-driven framework designed to enhance football club transfer strategies by predicting the market value of young players and optimizing player acquisitions. The approach integrates predictive modeling with optimization techniques to support informed recruitment decisions.

The study begins by constructing two original datasets:
- **Player Dataset**: Focused on individual player performance metrics.
- **Team Dataset**: Aggregated statistics at the team level to capture contextual performance.

Using these datasets, the research explores relationships between key performance indicators and market valuation, placing emphasis on robust feature engineering and exploratory data analysis.

A predictive model is developed to estimate the market value of young football talents using historical and performance-related variables. Based on this, an optimization model is implemented using Pyomo and the Gurobi solver to help clubs select the most suitable players under budgetary and squad composition constraints.

By combining machine learning, statistical analysis, and operations research, this framework supports strategic and evidence-based decision-making in professional football recruitment.

## Repository Structure

- `data_scraping_and_preperation/`: Scripts and raw data used for assembling and cleaning the player and team datasets.
- `market_value_prediction/`: Jupyter notebooks and scripts used to train and evaluate machine learning models for player market value estimation.
- `optimization/`: Code for the Pyomo optimization model, role detection via clustering, and player selection algorithms.
- `visualizations/`: Optional radar charts, heatmaps, and plots to support analysis and reporting.
- `README.md`: This file.

