# Bike-Sharing-Demand-Prediction

<b>Problem Statement</b><br>
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.<hr>

<strong>Describing DataSet</strong><br>
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

<strong>Attribute Information:</strong><br>
Date : year-month-day<br>
Rented_Bike_Count - Count of bikes rented at each hour<br>
Hour - Hour of he day<br>
Temperature-Temperature in Celsius<br>
Humidity - %<br>
Windspeed - m/s<br>
Visibility - 10m<br>
Dew point temperature - Celsius<br>
Solar radiation - MJ/m2<br>
Rainfall - mm<br>
Snowfall - cm<br>
Seasons - Winter, Spring, Summer, Autumn<br>
Holiday - Holiday/No holiday<br>
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)<br>
<hr>
<b>Algorithms for Model Training</b>

A model defines the relationship between features and label.A feature is an input variable—the x variable in simple linear regression.A label is the thing we're predicting—the y variable in simple linear regression.Training means creating or learning the model.In order to build the predictive model, it's time to implement some of the model training on the above selected feature.
<br>
Following algorithms have been used for predictions:-<br>

1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. KNeighborsRegressor
5. Random Forest Regression
<br>
  <b>Boosting</b><br>

  Boosting is a method used in machine learning to reduce errors in predictive data analysis.Boosting improves machine models' predictive accuracy and performance by    converting multiple weak learners into a single strong learning model. Machine learning models can be weak learners(have low prediction accuracy, similar to random guessing,prone to overfitting) or strong learners(higher prediction accuracy). Boosting converts a system of weak learners into a single strong learning system. There are many boosting algorithms which impart additional boost to model’s accuracy:

6. GradientBoostingRegressor - aggregates the results of each decision tree along the way to calculate the final result
7. XGB Regressor - provides parallel tree boosting,trees grow depth-wise
8. Light-BGM - trees grow leaf-wise
