# Air-Quality-Analysis-and-_Prediction
# Introduction
Problem: Rising air pollution impacts health and environment.(like due rising air pollution it affects humans birds and environment pollution etc.. can occur)
Goal: Predict AQI to enable early warnings using ML.(like we can easily inform the factory and the nearby people for example wear oxigen mask,try to avoide unnecessary travel,if anyone struggleing with breathing problem try to keep inhaler)
Benefits: Informed public, preventive actions.


# objectives
Perform EDA to understand pollution patterns.
• Correlate pollutants with AQI.
• Predict AQI using regression models.
• Use Power BI for insightful visualizations.


# Dataset Overview
• Source: Kaggle 
• 29,531 rows × 16 columns.
• Features: PM2.5, PM10, NOx, CO, Benzene, etc.
• Target: AQI   (air quality index)
• Challenges: Many missing values, feature imbalance.


# Methodology
 Understand the data : import  librariesa, cheking the  null values
Visualization: using hist plot and boxplot 
 Data Cleaning: Handle missing/null values.
Feature Engineering: Splitting into year, month, day helps build time-based insights.


# Correlation : Identify strong relationships between features
Outlier Detection :  using boxplot identify so many outliers in the dataset
Outlier removing : Function to remove outliers using the IQR method 
Initial Modeling :  using  LinearRegression
Evaluation: RMSE, R² 


# Model Selection & Implementation
 Models Used: Linear Regression, Decision Tree, Random Forest.
• Reasons: Simplicity, performance on non-linear data.
• Evaluation Metrics: RMSE, R² .
• Tools: Scikit-learn, Pandas.


# Evaluation & Results
R² Score: 0.780456820863235 
Mean Absolute Error (MAE): 0.208786914557602 
Mean Squared Error (MSE): 0.08007401882030216


# power bi Dashboard Overview
 The KPI cards quickly show the overall AQI status.
 The pie chart helps visualize how many days fall under each AQI category. 
The bar chart reveals the top 10 most polluted cities, helping target areas for improvement.
This map shows how air quality varies across different cities in India. It uses colored bubbles to represent pollution levels based on AQI.

# time-based trends
This line chart shows the yearly average AQI from 2015 to 2020
This horizontal bar chart compares the monthly AQI averages across all cities.
This table gives us a detailed monthly breakdown of AQI values for each year.
This scatter chart shows how the AQI values are distributed by category (Good, Moderate, Poor, etc.)

# polluatant - wise analysis
Clustered Bar Chart – Average of Pollutants by PM10 Level : On the left side, we have a bar chart that shows the average levels of four major pollutants — PM2.5, NO2, SO2, and CO — grouped by PM10 readings.
 Line Chart – Yearly Trend of All Major Pollutants .This line chart shows the year-wise sum of major pollutants, including PM2.5, NO2, NOx, SO2, O3, and PM10 count.

#  Conclusion
  ML helps track and predict pollution trends( ML can analyze historical  air quality data to identify  patterns and predict future pollution levels)

• Visualizations support awareness.(charts , graphs and dashboard make air quality data easier to understand for both experts and the public)

• Future: Real-time AQI, Time Series models, Deployment.
Real-time AQI:-building systems that display the current air quality instantly using live sensor data 
Time series models:- these are ML models designed for data over time to forecast future values 
Deployment :- putting the ML model and dashboard into a real-world application (like website or mobile app) for public use 

Thanks
