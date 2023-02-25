![petter-rudwall-GVLhWdib3BU-unsplash](https://user-images.githubusercontent.com/102637138/221340129-e29372ce-f3b8-4b94-8719-5d456f9feb76.jpg)

# Project Goal
This project will analyze and predict air quality data in India by creating a time series model to predict daily PM2.5 readings. Particulates (PM2.5) are airborne particles smaller than 2.5 microns (micrometers). The various materials contained in PM2.5 can cause various respiratory tract disorders such as acute respiratory infections (ARI), lung cancer, cardiovascular disease, premature death, and chronic obstructive pulmonary disease (Novirsa et al., 2012; WHO , 2006). Doing research, understanding, and predicting air quality can prevent and overcome problems that can occur. The aims of this project are:
1. Prepare time series data for analysis
2. Clean data and visualize
3. Create an autoregression model
4. Improve the model with walk forward validation

This project consists of three parts:
1. Prepare Data
    - Imports
    - Explore
    - Splits
2. Build Model
    - Baseline Models
    - Iterate
    - Evaluate
3. Communication Results

# Data Description
The dataset used has 36192 observations and 6 variables related to time series and PM2.5. The variable data type contains 4 integers, 1 float, and 1 datetime. However, we will not use all of them. I will focus on the time series variables which contain information about time and the PM2.5 variable will be our prediction target. A brief explanation of each variable is as follows:
1. Timestamp: Timestamp in the format YYYY-MM-DD HH:MM:SS
2. Year: Year of the measure
3. Month: Month of the measure
4. Day: Day of the measure
5. Hour: Hour of the measure
6. PM2.5: Fine particulate matter air pollutant level in air

# References

https://spureconomics.com/interpreting-acf-and-pacf-plots/

https://otexts.com/fpp2/AR.html

https://neptune.ai/blog/time-series-prediction-vs-machine-learning

https://www.kaggle.com/code/satishgunjal/tutorial-time-series-analysis-and-forecasting
