# Rainfall Prediction Classifier

## Project Overview
This project builds a machine learning model to predict whether it will rain tomorrow based on historical weather data from Australia.

## Dataset
The dataset contains daily weather observations from multiple Australian weather stations. The target variable is `RainTomorrow`, indicating whether it rained the next day.

## Features
- **Temperatures**: MinTemp, MaxTemp, TempRange
- **Humidity**: Humidity9am, Humidity3pm, HumidityChange
- **Pressure**: Pressure9am, Pressure3pm, PressureChange
- **Wind**: WindSpeed9am, WindSpeed3pm
- **Cloud cover**: Cloud9am, Cloud3pm, CloudCover
- **Rainfall**: Rainfall
- **And other weather parameters**

## Models Implemented
1. Logistic Regression
2. Random Forest Classifier (Default)
3. Random Forest Classifier (Tuned)

## Results Summary
- **Best Model**: Random Forest with hyperparameter tuning
- **Accuracy**: ~87%
- **True Positive Rate**: ~89%

## Installation
```bash
pip install -r requirements.txt
