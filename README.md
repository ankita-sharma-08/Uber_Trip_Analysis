# Project Name : Uber_Trip_Analysis
For the Analysis used the following dataset
https://drive.google.com/file/d/1uj0xGqt3t7w6AgoTNq8SksR2Ci3bbWJ1/view

# 1.1. Dataset Overview

•	Source: Uber-Jan-Feb-FOIL.csv 

•	Size: The dataset contains multiple records of Uber trips.

## Key Features:-

•	date: Date of the trip

•	trips: Number of trips taken

•	active_vehicles: Number of active vehicles

•	dispatching_base_number: Identifier for the dispatching base

# 1.2. Data Preprocessing

•	Datetime format was applied to the date column. 

•	Label Encoding was used to encode the dispatching_base_number. 

•	Data integrity was ensured by checking for null values and duplicates.

# 1.3. Analysis of Exploratory Data (EDA)

•	Visualized the distribution of trips using a histogram.

•	Created a correlation heatmap to understand relationships between features.

# 1.4. Model Development

•	Features and Target Variable:

•	Features (x): active_vehicles

•	Target (y): trips

•	Model Selection: Random Forest Regressor and XGBoost Regressor were used for predictions.

•	Model Evaluation:
          Mean Squared Error (MSE) and R-squared (R²) were calculated to assess model performance.

# 1.5. Results 

•	Random Forest Model: 

•	MSE ( mean Square Error) for RandomForestRegressor : 5617775.980422676

•	R²:  0.9479013678069232

•	XGBoost Model:  

•	MSE ( mean Square Error) for xgb.XGBRegressor : 5617775.980422676

•	R²:  0.9479013678069232

•	Visualized predictions against actual trips for both models.
