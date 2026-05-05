# DS4002-CS3: When Will the Lights Go Out?

## Overview
This repository contains materials for a DS 4002 case study based on Project 2: predicting 
the time of day a U.S. power outage will occur using machine learning. The case study asks 
students to reproduce and extend the original analysis by engineering at least one new 
time-based feature and comparing three models: Linear Regression, Random Forest, and XGBoost.

## Data Source
Event-Correlated Outage Dataset in America (2023), Data.gov — approximately 77,000 U.S. 
power outage records.

## Repository Contents
- Hook Document (PDF) — introduces the case study scenario
- Rubric (PDF) — outlines the task, deliverables, and evaluation criteria
- MATERIALS/
  - SCRIPTS/ — cleaning, EDA, and modeling notebooks
  - DATA/ — raw and cleaned datasets
  - OUTPUT/ — performance table and EDA visualizations
  - Articles/ — reference materials

## To Reproduce the Analysis
1. Download the data from MATERIALS/DATA/
2. Run `cleaning.ipynb` first to generate `cleaned_data.csv`
3. Run `EDA_PowerOutages.ipynb` for exploratory analysis
4. Run `model_and_analysis.ipynb` for modeling and evaluation

## Required Packages
pandas, matplotlib, seaborn, numpy, scikit-learn, xgboost
