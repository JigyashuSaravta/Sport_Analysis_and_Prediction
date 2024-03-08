# Sport_Analysis_and_Prediction

## Football Player Performance Prediction
This repository contains the code and datasets used in our project on predicting football (soccer) player performance metrics, utilizing statistical analysis and machine learning techniques. Our goal was to leverage various football player features to predict a player's performance, specifically focusing on playtime (minutes of playing) based on a dataset of 532 entries featuring player's club, nationality, rank, age, passes attempted, penalty goals, and more.

## Project Overview
In this era, data analytics is transforming various sectors, including sports. Inspired by teams like Leicester City FC, FC Barcelona, and the German national team, our project aimed to harness the power of analytics in football to predict player performance metrics effectively.

## Objectives
To predict a player's playtime using statistical analysis and machine learning.
To understand the nuanced interplay between various dataset features and a player's playtime.
To leverage correlation analysis and the Tukey HSD test to identify significant predictors of playtime.
To implement linear regression and Lasso regularization models for accurate predictions.

## Dataset
The project utilized data from the English Premier League 2020-21 season, comprising 532 unique entries with features like name, club, nationality, position, age, number of matches played, goals scored, penalty attempted, etc., of a football player.

## Methodology
Data Extraction: Used English Premier League 2020-21 data for analysis.
Exploratory Data Analysis (EDA): Conducted to understand relationships between features and playtime.
Correlation Analysis: Identified features with a greater impact on playtime.
Analysis of Variance (ANOVA): Tested for differences among means of the population.
Tukey HSD Test: Assessed significance of differences between pairs of group means.
Model Building: Implemented linear regression and Lasso regularization models.

## Results
The linear regression model achieved an R-squared value of approximately 0.996, indicating a high level of predictive accuracy.
Lasso regularization was used to refine the model further, performing feature selection and improving model interpretability without sacrificing accuracy.
Cross-validation confirmed the robustness and generalizability of our models across different subsets of data.
Technologies Used
Python for data analysis and model building.
Libraries such as Pandas, NumPy, Matplotlib, Seaborn, scikit-learn for various stages of the project from data preprocessing to model evaluation.

## Conclusion
This project illustrates the potential of data analytics in enhancing player assessment and team strategy in football. By applying machine learning techniques, we developed models that not only predict player performance with high accuracy but also offer insights into the importance of various features in determining playtime.
