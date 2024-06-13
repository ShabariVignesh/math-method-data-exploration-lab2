# Data Exploration and Analysis

## Overview
This repository contains the code and documentation for exploring and analyzing datasets using various statistical and machine learning techniques. The primary focus is on recommender systems, house price prediction, and life expectancy prediction.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Recommender System](#recommender-system)
- [House Prices Prediction](#house-prices-prediction)
- [Life Expectancy Prediction](#life-expectancy-prediction)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)

## Introduction
This project involves the application of mathematical methods for data analysis, including Singular Value Decomposition (SVD) for recommender systems, linear regression models for house price prediction, and various regression techniques for predicting life expectancy.

## Datasets
- **MovieLens 1M Dataset**: Used for building the movie recommender system.
- **HousePrice.csv**: Contains data for predicting house prices.
- **LifeExpectancy.csv**: Used for predicting life expectancy based on health and socio-economic factors.

## Recommender System
### Objective
To explore movie recommendations through Singular Value Decomposition (SVD).

### Process
1. **Data Loading**: Movies and ratings data are loaded from the MovieLens dataset.
2. **Data Preprocessing**: Movies and ratings datasets are merged and normalized.
3. **SVD Application**: Decompose the user-movie matrix using SVD.
4. **Cosine Similarity**: Compute cosine similarity to recommend movies.

### Files
- `recommender_system.py`: Contains the code for building the recommender system.
- `movies.dat` and `ratings.dat`: MovieLens dataset files.

## House Prices Prediction
### Objective
To predict house prices using linear and polynomial regression models.

### Process
1. **Data Exploration**: Summary statistics and visualization of key features.
2. **Regression Models**: Implementation of linear regression, polynomial regression, and RANSAC regression.
3. **Model Evaluation**: Calculation of R-squared values and visualization of results.

### Files
- `house_price_prediction.py`: Contains the code for predicting house prices.
- `HousePrice.csv`: Dataset file for house prices.

## Life Expectancy Prediction
### Objective
To predict life expectancy based on various health and socio-economic factors.

### Process
1. **Data Preprocessing**: Handling missing values and outliers.
2. **Feature Engineering**: Label encoding and data normalization.
3. **Regression Models**: Implementation of ordinary least squares, mini-batch gradient descent, and stochastic gradient descent.
4. **Model Evaluation**: Mean Absolute Error (MAE) calculation for model performance.

### Files
- `life_expectancy_prediction.py`: Contains the code for predicting life expectancy.
- `LifeExpectancy.csv`: Dataset file for life expectancy.

## Results
The results of each model are documented in the respective sections of the code files. Visualizations and model performance metrics are included to illustrate the effectiveness of the applied techniques.

## Conclusion
This project demonstrates the application of mathematical and algorithmic approaches in data analysis. Each section provides insights into the methods used and their respective outcomes, highlighting the potential of data-driven decision-making.

## Author
Shabari Vignesh
