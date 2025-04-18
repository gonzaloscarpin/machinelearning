# About this Project
This repository contains 18 different machine learning models used to predict cotton lint yield (kg/ha) based on a combination of genotypic, management, and environmental factors.

The dataset used in this project includes observations from field experiments conducted with multiple varieties across different sowing dates, years, and environmental conditions. The main goal is to explore and compare the predictive performance of various ML algorithms for modeling lint yield response.

🎯 Objective
To predict cotton lint yield using:

Sowing date (early vs. late)

Variety name and year of release

Main meteorological variables during the crop's critical period:

Mean maximum temperature (°C)

Mean minimum temperature (°C)

Cumulative heliophany (h)

Total precipitation (mm)

Solar radiation (MJ/m²)

Reference evapotranspiration (mm)

🤖 Machine Learning Models Implemented
The following ML methods were used to predict lint yield:

Random Forest

XGBoost

Generalized Random Forest (GRF)

Bayesian Additive Regression Trees (BART)

Bagged Decision Trees

Support Vector Machines - linear kernel

Support Vector Machines - polynomial kernel

RuleFit

Cubist Rule-Based Model

Linear Regression

Partial Least Squares (PLS)

k-Nearest Neighbors (kNN)

Multilayer Perceptron (MLP)

Multivariate Adaptive Regression Splines (MARS)

Bagged MARS

Bagged MLP

Classification and Regression Trees (CART)

Poisson Regression

Each method is implemented as a separate .qmd (Quarto) file and includes data preprocessing, model fitting, evaluation (e.g., RMSE), and visualization.


