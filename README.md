# Time Series Forecasting: GG Taxi Data Analysis

## American University of Armenia
### College of Science and Engineering
**Fall 2022**

---

## Contents

- [Abstract](#abstract)
- [Introduction](#introduction)
- [Literature Review](#literature-review)
- [Data Description](#data-description)
- [Methods](#methods)
- [Results](#results)
- [Conclusion](#conclusion)
- [Bibliography](#bibliography)
- [List of Figures](#list-of-figures)

---

## Abstract

In the competitive landscape of taxi services, leveraging technology and IT expertise is crucial for companies to gain a competitive edge. This project explores the benefits of time series analysis for GG taxi, focusing on tracking and predicting changes in customer demand over time to enable more efficient operations and resource allocation.

## Introduction

The project aims to analyze time series data to predict the daily quantity of orders for GG taxi service, providing insights into the company's business activity and helping allocate resources more efficiently during peak demand periods or slower times.

## Literature Review

Research by D. Khryashchev and V. Huy, along with S. Faghiha and others, explores various methods for predicting taxi orders, including the Markov prediction algorithm, ARIMA model, and deep learning LSTM models, highlighting the effectiveness of these approaches in forecasting taxi demand.

## Data Description

The analysis utilizes data from GG taxi in 2016, including completed and cancelled orders, merged from two datasets (`gg.rda` and `gg_all.rda`) to provide a comprehensive overview of the company's activity throughout the year.

## Methods

The project employs SARIMA, exponential smoothing, and VAR models to forecast the number of completed taxi orders and analyze the relationships between multiple variables over time, including completed and cancelled orders.

## Results

The SARIMA model was identified as the most effective for forecasting, with the research demonstrating the model's capability to predict the number of completed orders accurately. The VAR model also provided insights into the correlation between completed and cancelled orders.

## Conclusion

The time series analysis revealed SARIMA(5,1,0)(1,0,1)[7] as the best model for forecasting GG taxi's order volume, with findings indicating a decrease in taxi demand after the New Year period, closely mirroring real-world trends. The analysis underscores the potential of time series forecasting in enhancing operational efficiency for taxi firms.

## Bibliography

1. Denis Khryashchev, Huy V., December 2019, "Predicting Taxi and Uber Demand in Cities: Approaching the Limit of Predictability."
2. S. Faghiha, A. Shahb, Z. Wangb, A. Safikhanic, C. Kamgaa, November 2020, "Taxi and Mobility: Modeling Taxi Demand Using ARMA and Linear Regression."

## List of Figures

Figures 1 through 14 illustrate various aspects of the data analysis, including trends and seasonality in completed and cancelled orders, weekly order volume comparisons, and forecasting results from the SARIMA and VAR models.
