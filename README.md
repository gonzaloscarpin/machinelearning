# About this Project

This repository contains 17 different machine learning models used to predict cotton lint yield (kg/ha) based on a combination of genotypic, management, and environmental factors.

The dataset used in this project includes observations from field experiments conducted with multiple varieties across different sowing dates, years, and environmental conditions. The main goal is to explore and compare the predictive performance of various ML algorithms for modeling lint yield response.

## 🎯 Objective: to predict cotton lint yield using:

-   Sowing date (early vs. late)

-   Variety name and year of release

-   Main meteorological variables during the crop's critical period:

-   Mean maximum temperature (°C)

-   Mean minimum temperature (°C)

-   Cumulative heliophany (h)

-   Total precipitation (mm)

-   Solar radiation (MJ/m²)

-   Reference evapotranspiration (mm)

## 🤖 Machine Learning Models Implemented

The following ML methods were used to predict lint yield:

01 Random Forest

02 XGBoost

03 Bayesian Additive Regression Trees (BART)

04 Bagged Decision Trees

05 RuleFit

06 Cubist Rule-Based Model

07 Classification and Regression Trees (CART)

08 Elastic Net - Linear Regression

09 Poisson Regression

10 Partial Least Squares (PLS)

11 Support Vector Machines - linear kernel

12 Support Vector Machines - polynomial kernel

13 k-Nearest Neighbors (kNN)

14 Multivariate Adaptive Regression Splines (MARS)

15 Bagged MARS

16 Multilayer Perceptron (MLP)

17 Bagged MLP

Each method is implemented as a separate .qmd (Quarto) file and includes data preprocessing, model fitting, evaluation (e.g., RMSE), and visualization.
