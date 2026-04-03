# Enterprise Utility Model-Ready Dataset Preparation for Forecasting, Anomaly Detection, and Grid Reliability Analytics

## Project Overview
This project simulates how model-ready utility datasets can be prepared from smart meter, outage, operational, and weather data.

It is based on an enterprise pattern where multiple data domains must be cleaned, integrated, standardized, and feature-engineered before they are used for forecasting, anomaly analysis, or grid reliability analytics.

The project includes:
- raw utility dataset generation
- processed dataset preparation
- model-ready feature engineering
- forecasting-ready dataset creation
- anomaly and outage-risk feature generation
- simple ML examples

## Business Goal
The goal of this project is to show how integrated and feature-ready datasets support better operational decision-making and more proactive analytics.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab


📈 Forecasting Model Performance:

The model achieved a Mean Absolute Error of 7.41, which means the predicted daily energy usage is on average off by about 7.41 units.

This shows the model is able to capture usage patterns reasonably well using features like recent usage, operational data, and weather conditions.

The result confirms that the dataset is suitable for forecasting and can be further improved with tuning and more data.


📊 Feature Importance Analysis

This analysis shows which features have the most impact on predicting daily energy usage.

The model identified recent usage patterns as the most important factors.
Features like 7 day average usage and previous day usage have the highest influence, which means past consumption behavior plays a key role in forecasting future usage.

Weather related features such as temperature and wind speed also contribute, showing that external conditions affect energy consumption.

Overall, this helps explain how the model makes predictions and highlights the key drivers behind energy usage. It also provides useful direction for improving forecasting by focusing on the most impactful features.
