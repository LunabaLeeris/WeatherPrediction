# What is this about
This is a machine learning experimentation. Specifically, it's a project I made to explore how Gaussian Discriminant Analysis Can be implemented in python. 

# Goal
This project's goal is to create a model for predicting weather, which can either be sunny, snowy, rainy or cloudy, from a dataset gathered at 
https://www.kaggle.com/datasets/nikhil7280/weather-type-classification

# Features
The features includes:
**Temperature (numeric)**: The temperature in degrees Celsius, ranging from extreme cold to extreme heat.

**Humidity (numeric)**: The humidity percentage, including values above 100% to introduce outliers.

**Wind Speed (numeric)**: The wind speed in kilometers per hour, with a range including unrealistically high values.

**Precipitation (%) (numeric)**: The precipitation percentage, including outlier values.

**Cloud Cover (categorical)**: The cloud cover description.

**Atmospheric Pressure (numeric)**: The atmospheric pressure in hPa, covering a wide range.

**UV Index (numeric)**: The UV index, indicating the strength of ultraviolet radiation.

**Season (categorical)**: The season during which the data was recorded.

**Visibility (km) (numeric)**: The visibility in kilometers, including very low or very high values.

**Location (categorical)**: The type of location where the data was recorded.

**Weather Type (categorical)**: The target variable for classification, indicating the weather type.

# Results
After implementation, the accuracy was calculated which turned out to be **75%**. This means that although computationally efficient, Gaussian Discriminant Analaysis, 
is not that great of an approach for the given dataset. 
