# Modeling Deaths for Diabetes & Kidney Diseases, Globally

This project aims to use historically available data about death rates for diabetes and kidney diseases to predict future death rates across various countries. By leveraging machine learning models, the project seeks to provide valuable insights that can aid government and health officials in mitigating the impact of these diseases.

## Table of Contents

- [Overview](#overview)
- [Data Sources](#data-sources)
- [Methods](#methods)
- [Results](#results)
- [Discussion and Conclusion](#discussion-and-conclusion)
- [Contributors](#contributors)

## Overview

The death rates for diabetes and kidney diseases are influenced by various economic and health-related factors, such as government health expenditure, a country's GDP, population, access to technology and internet, and access to sanitation facilities. This project explores the relationships between these factors and death rates, with the goal of building a predictive model that can estimate future death rates based on historical data.

## Data Sources

The data for this project was collected from the following sources:

- **Global Burden of Disease (GBD)**: A comprehensive database maintained by the Institute for Health Metrics and Evaluation (IHME), providing mortality and disability data across countries, time, age, and sex.
- **World Development Indicators**: A compilation of relevant, high-quality, and internationally comparable statistics about global development and the fight against poverty, maintained by the World Bank.

## Methods

A detailed description of the methods used in this project can be found in the separate [Methods document](https://docs.google.com/document/d/1Y4MWRae78cLqWdwoEYex4NoBRUJmWwVRWy6I6k-A6nQ/edit?usp=sharing).

## Results

The project conducted exploratory data analysis to gain insights into the relationships between various factors and death rates. A predictive multivariable linear regression model was developed, achieving a low RMSE score of 0.24 when predicting 2019 values. This indicates that the model is a fairly good predictor of national diabetes and kidney disease death rates, at least a few years beyond the testing data available.

## Discussion and Conclusion

The results of this project have significant implications for government officials, healthcare providers, and public health experts, as they provide valuable insights into future death rates for diabetes and kidney diseases. These insights can inform policy decisions, resource allocation, and preventative measures to curb the incidence of these diseases. While the current model shows promising results, there is room for improvement by incorporating additional demographic and health-related factors and using advanced machine learning techniques.

## Contributors

- Shreyas Dikshit
- Amare Diotte
- Taylor Goodwin
- Aditi Gupta
