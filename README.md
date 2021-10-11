# Energy-Appliances-Prediction
Aim: Predection the energy use of appliances
Data Attributes

date - time year-month-day hour:minute:second

Appliances - energy use in Wh (Dependent variable)

lights - energy use of light fixtures in the house in Wh (Drop this column)

T1 - Temperature in kitchen area, in Celsius

RH1 - Humidity in kitchen area, in %

T2 - Temperature in living room area, in Celsius

RH2 - Humidity in living room area, in %

T3 - Temperature in laundry room area

RH3 - Humidity in laundry room area, in %

T4 - Temperature in office room, in Celsius

RH4 - Humidity in office room, in %

T5 - Temperature in bathroom, in Celsius

RH5 - Humidity in bathroom, in %

T6 - Temperature outside the building (north side), in Celsius

RH6 - Humidity outside the building (north side), in %

T7 - Temperature in ironing room, in Celsius

RH7 - Humidity in ironing room, in %

T8 - Temperature in teenager room 2, in Celsius

RH8 - Humidity in teenager room 2, in %

T9 - Temperature in parents room, in Celsius

RH9 - Humidity in parents room, in %

T_out - Temperature outside (from Chievres weather station), in Celsius

Pressure - (from Chievres weather station), in mm Hg RHout

Humidity - outside (from Chievres weather station), in %

Wind speed - (from Chievres weather station), in m/s

Visibility - (from Chievres weather station), in km

Tdewpoint - (from Chievres weather station), Â°C

rv1 - Random variable 1, nondimensional

rv2 - Random variable 2, nondimensional

Project Summary
● As the first step, we understand the data & checked for null values, and outliers and performed EDA to get better understanding of variables .
● As part of data pre-processing, we performed feature scaling and outlier removal
● As so we have a Timestamp in our data, we needed to see the periodicity and trend of our dependent and independent variables.
● We tried multiple simple models and multiple advanced models with performed hyperparameter tuning and cross validation.
● Models Built: Linear Regression, SVR, RandomForest, Gradient Boosting XGBoost
● Advanced Models: Stacking Regressor, Voting Regressor, Average Ensemble
● Based on our targeted evaluation metric - RMSE and R2 scorel, we chose Stacking Regressor as the suggested model.
