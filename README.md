# Melbourne Housing Price Prediction Project

## Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Data Description](#data-description)
- [Methodology](#methodology)
  - [Data Exploration](#data-exploration)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Building](#model-building)
  - [Model Evaluation](#model-evaluation)
- [Insights from Exploratory Data Analysis (EDA)](#insights-from-exploratory-data-analysis-eda)
- [Model Evaluation and Results](#model-evaluation-and-results)
  - [Linear Regression](#linear-regression)
  - [Lasso Regression](#lasso-regression)
  - [Cross-Validation](#cross-validation)
- [Conclusion and Recommendations](#conclusion-and-recommendations)
- [Future Directions](#future-directions)

## Overview

This project aims to analyze and predict housing prices in Melbourne using various machine learning models. The objective is to understand the factors affecting housing prices and to build a reliable predictive model to aid stakeholders in the real estate market.

## Business Problem

The real estate market's dynamics are influenced by numerous factors, including location, property type, and size. Accurate prediction of housing prices is crucial for both buyers and sellers to make informed decisions. 

## Data Description

The dataset encompasses various features such as location, number of rooms, type of property, method of sale, and others, providing a comprehensive overview of factors influencing housing prices in Melbourne.

## Methodology

#### Data Exploration
Initial analysis focused on understanding the dataset through visualization and statistical analysis.

#### Data Preprocessing
Included cleaning and preparing the data for modeling, handling categorical variables, and addressing missing values.

#### Model Building
Different models, including Linear Regression and Lasso Regression, were implemented to predict housing prices.

#### Model Evaluation
Models were assessed using metrics like RMSE, R-square, AIC, and BIC.

## Insights from Exploratory Data Analysis (EDA)

- The average number of rooms across all regions is 3, indicating a preference for moderate-sized properties.
- A clear correlation exists between the number of rooms and housing prices.
- The Southern Metropolitan region has higher prices, highlighting regional disparities in housing affordability.
- A notable number of properties were constructed from 2000 to 2020, with a spike in constructions between 1960 to 1970.
- High collinearity was observed between 'rooms' and 'bedroom2', suggesting redundancy.

## Model Evaluation and Results

### Linear Regression
- **Train Set**: RMSE of 0.266, R-square of 0.75
- **Test Set**: RMSE of 0.306, R-square of 0.63

### Lasso Regression
- Demonstrated robustness in out-of-sample prediction with an RMSE of 0.540 in cross-validation.

### Cross-Validation
- Affirmed the consistency of the Linear Regression model over Lasso Regression in unseen data performance.

## Conclusion and Recommendations

The project provides valuable insights into the Melbourne housing market, emphasizing the importance of regional differences and property characteristics. Linear Regression emerged slightly superior in terms of generalizability and consistency.

### Future Directions

- Exploring more sophisticated models and including additional features could enhance prediction accuracy.
- Incorporating granular data, such as neighborhood amenities and economic indicators, could offer a more nuanced understanding of housing prices.




