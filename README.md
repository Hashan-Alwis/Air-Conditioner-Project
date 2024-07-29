# IoT Air Conditioning System - Machine Learning Component

This project is the machine learning part of an IoT system designed for air conditioning. It involves time series analysis to forecast temperature, humidity, and CO2 levels for the next 10 minutes based on collected data from lecture rooms. Additionally, regression models were developed to predict optimal temperature and humidity and measure CO2 levels in the room.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Time Series Analysis](#time-series-analysis)
- [Regression Models](#regression-models)


## Overview

This project aims to improve air conditioning systems in lecture rooms by forecasting temperature, humidity, and CO2 levels. By analyzing past data, the system can make accurate predictions for the next 10 minutes, helping maintain optimal environmental conditions.

## Dataset

The dataset consists of collected temperature, humidity, and CO2 data from lecture rooms. The data is segmented into 5 sequences of 10-minute intervals, making a total of 50 minutes, to predict the next 10-minute values.

## Time Series Analysis

Time series analysis is used to forecast the following:
- Temperature for the next 10 minutes
  ### model evaluation
  ![temp-ts-prediction vs actual](https://github.com/user-attachments/assets/350988a8-94fe-4b76-964c-704ced730fba)
- Humidity for the next 10 minutes
  ### model evaluation
  ![humidity-ts-actual vs predicted](https://github.com/user-attachments/assets/f30ff452-7d6d-4e5a-951f-4bb82fde0143)
- CO2 levels for the next 10 minutes
  ### model evaluation
  ![co2-ts-actual vs predicted](https://github.com/user-attachments/assets/340e33b4-ff09-4ee2-917c-a4ffb0e8ba49)

The analysis leverages past data to make accurate predictions and ensure the lecture rooms remain comfortable and safe.

## Regression Models

In addition to time series forecasting, three regression models were developed for:
1. Predicting optimal temperature
2. Predicting optimal humidity
3. Measuring CO2 levels

These models help in maintaining the optimal conditions in the lecture rooms by providing real-time adjustments based on the predictions.

