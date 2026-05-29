# Online News Popularity Prediction

## Overview
Predicting the popularity (share count) of online news articles using 
machine learning regression models. This project identifies key factors 
that influence article virality — including word count, images, keywords, 
publication timing, and social media engagement.

## Objective
Build and compare four ML regression models to predict article share 
counts, providing insights for digital media content strategy optimisation.

## Dataset
Online News Popularity dataset — real-world news article data with 
multiple features including content type, word count, publication day, 
and social media metrics.

## Models & Results

| Model | MAE | MSE | RMSE | R² |
|---|---|---|---|---|
| Linear Regression | — | 0.8981 | 0.9477 | — |
| Decision Tree | — | 1.7694 | 1.3302 | — |
| Random Forest | 0.7481 | 0.8879 | — | 0.1186 |
| SVR | 0.6739 | 0.9715 | — | 0.0357 |

**Best MAE:** SVR (0.6739) — most accurate predictions
**Best RMSE:** Linear Regression (0.9477) — best overall fit

## Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Plotly

## Pipeline
1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature preprocessing
4. Model training — 80/20 train/test split
5. Model evaluation and comparison
6. Results visualisation with Plotly

## Key Finding
SVR achieved the lowest MAE but limited R² — suggesting the dataset's 
variability is challenging to explain with standard regression models. 
Linear Regression provided the best overall balance of simplicity and fit.
