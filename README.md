# Temperature_Prediction_Using_Linear_Regression

Project Overview:
      1) This project predicts Average Temperature (°C) using Multiple Linear Regression       based on historical weather data collected from weather stations across India.
      2)The model analyzes meteorological parameters such as minimum temperature,        maximum        temperature, wind speed, air pressure, and elevation to estimate average temperature     with high accuracy.
      3)  The project demonstrates how Machine Learning can be applied to weather forecasting      using simple and interpretable regression techniques.

Objectives:
    1) Predict average temperature using Linear Regression.
    2) Perform data preprocessing and feature engineering.
    3) Evaluate model performance using regression metrics.
    4) Analyze feature importance and prediction accuracy.
    5) Build a scalable and interpretable weather prediction system.

    
Dataset Information:
    Dataset: India Weather Rainfall Dataset
    Total Records: 970,339
    Weather Stations: 406
    States Covered: 32
    Time Period: 2015 – 2025

Features Used:
   min_temp: Minimum Temperature (°C)
   max_temp: Maximum Temperature (°C)
   wind_speed: Wind Speed (km/h)
   air_pressure: Air Pressure (hPa)
   elevation: Elevation (m)

Target Variable:
    avg_temp (Average Temperature °C)

Technologies Used
    1) Python
    2) Pandas
    3) NumPy
    4) Matplotlib
    5) Scikit-Learn
    6) Jupyter Notebook
    7) Git & GitHub  

Machine Learning Workflow:
   1) Load weather dataset
   2) Handle missing values
   3) Select important features
   4) Split dataset into training and testing sets
   5) Apply StandardScaler
   6) Train Linear Regression model
   7) Evaluate model performance
   8) Visualize results
   9) Save trained model using Pickle
   
Model Performance:
  R² Score: 0.9765
  RMSE: 0.84°C
  MAE: 0.57°C

Performance Summary:
    97.65% variance explained by the model.
    Average prediction error below 1°C.
    Excellent performance across different climatic regions.

Visualizations:
   1) Actual vs Predicted Plot
      <img width="887" height="755" alt="Screenshot 2026-06-13 121052" src="https://github.com/user-attachments/assets/74770715-8eb6-4233-b343-887afe3f7a2c" />

  2) Residual Plot
     <img width="893" height="751" alt="Screenshot 2026-06-13 121113" src="https://github.com/user-attachments/assets/05eceacc-3dc6-4fb0-837f-0a69bb59a2fb" />

  3) Feature Importance Chart
     <img width="881" height="732" alt="Screenshot 2026-06-13 121139" src="https://github.com/user-attachments/assets/2c7d6e89-d71e-4135-9eb3-afe0699fec99" />

  4) Residual Distribution Histogram
     <img width="872" height="741" alt="Screenshot 2026-06-13 121202" src="https://github.com/user-attachments/assets/6ea4fb6f-2bef-46f9-8c8f-e01660f63cdb" />

Sample Prediction:
Input:
   Min Temp = 8°C
   Max Temp = 18°C
   Wind Speed = 15 km/h
   Air Pressure = 1015 hPa
   Elevation = 216 m

Output:
   Predicted Average Temperature = 12.66°C    

Installation:
   git clone https://github.com/yourusername/Temperature-Prediction-Using-Linear-Regression.git

   cd Temperature-Prediction-Using-Linear-Regression

   pip install -r requirements.txt

Run Project:
  jupyter notebook

Open:
  temperature_prediction.ipynb
  Run all cells.

Author:
  Malaravan R
  Python Full Stack Developer & Machine Learning Enthusiast

   

   


      

   
   

