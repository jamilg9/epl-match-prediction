# ⚽ EPL Match Outcome Prediction

## Overview
This project builds machine learning models to predict English Premier League match outcomes using 2023–2024 season data. The objective is to evaluate team performance metrics and determine which factors most strongly influence match results.

## Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest

## Data
- `matches.csv` – Raw match-level data
- `epl_merged.csv` – Cleaned and feature-engineered dataset

## Methodology
1. Data cleaning and feature engineering
2. Train/test split
3. Model training and evaluation
4. Performance comparison

## Results
The Logistic Regression model achieved the strongest predictive performance, outperforming Random Forest and Decision Tree models.

Key predictive features included:
- Goal differential
- Home scoring strength
- Defensive metrics

## Visualization
- `visuals/decision_tree.png`
- `Tableau/EPL.twb` – Interactive Tableau dashboard

## Product Perspective
This modeling framework could be extended to:
- Betting market analysis
- Team strategy optimization
- Performance scouting tools

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib, Tableau