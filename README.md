
# Predict average temperature in Riyadh using ARIMA model
## Dataset Description:
- The weather riyadah Dataset contain informations about weather in Riyadh across period of time which is in this case days start from 2008 to 2018, with 13 attributes that describes it which are:
   - Date,Temperature_Max,Temperature_avg,Temperature_Min,Dew_Point_Max,Dew_Point_Avg,Dew_Point_Min,
Humidity_Max,  Humidity_Min ,Wind_speed_Max, Wind_speed_Min,Pressure_Max,Pressure_Min.
- Dataset link: https://www.kaggle.com/osamah2018/riyadh-weather
## Problem Definition:

 - with the use of Temperature_Max,Temperature_Min,Dew_Point_Max,Dew_Point_Avg,Dew_Point_Min,Humidity_Max, Humidity_Min   ,Wind_speed_Max, Wind_speed_Min,Pressure_Max,Pressure_Min features and the goal is to create a time series problem and predict Temperature_avg in the next days. 
# Conclusion
- It seems that the model needs to be improved maybe using monthly values to predict Average Temperature values or even yearly and compare between them instead of days which didn't make a good prediction.
