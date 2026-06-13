# Temperature Prediction Using Linear Regression

## Project Overview

This project predicts **Average Temperature (°C)** using **Multiple Linear Regression** based on historical weather data collected from weather stations across India.

The model analyzes meteorological parameters such as:

- Minimum Temperature
- Maximum Temperature
- Wind Speed
- Air Pressure
- Elevation

to estimate average temperature with high accuracy.

---

## Objectives

- Predict average temperature using Linear Regression.
- Perform data preprocessing and feature engineering.
- Evaluate model performance using regression metrics.
- Analyze feature importance and prediction accuracy.
- Build a scalable and interpretable weather prediction system.

---

## Dataset Information

| Attribute | Details |
|------------|----------|
| Dataset | India Weather Rainfall Dataset |
| Total Records | 970,339 |
| Weather Stations | 406 |
| States Covered | 32 |
| Time Period | 2015 – 2025 |

---

## Features Used

### Input Features

| Feature | Description |
|----------|------------|
| min_temp | Minimum Temperature (°C) |
| max_temp | Maximum Temperature (°C) |
| wind_speed | Wind Speed (km/h) |
| air_pressure | Air Pressure (hPa) |
| elevation | Elevation (m) |

### Target Variable

| Variable | Description |
|----------|-------------|
| avg_temp | Average Temperature (°C) |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
- Git
- GitHub

---

## Machine Learning Workflow

1. Load weather dataset
2. Handle missing values
3. Select important features
4. Split dataset into training and testing sets
5. Apply StandardScaler
6. Train Linear Regression model
7. Evaluate model performance
8. Visualize results
9. Save trained model using Pickle

---

## Model Performance

| Metric | Value |
|----------|--------|
| R² Score | 0.9765 |
| RMSE | 0.84°C |
| MAE | 0.57°C |

### Performance Summary

- 97.65% variance explained by the model.
- Average prediction error below 1°C.
- Excellent performance across different climatic regions.

---

## Sample Prediction

### Input

```text
Min Temperature : 8°C
Max Temperature : 18°C
Wind Speed      : 15 km/h
Air Pressure    : 1015 hPa
Elevation       : 216 m
```

### Output

```text
Predicted Average Temperature : 12.66°C
```

---

## Visualizations

### 1. Actual vs Predicted Temperature

<img width="887" height="755" alt="Screenshot 2026-06-13 121052" src="https://github.com/user-attachments/assets/74770715-8eb6-4233-b343-887afe3f7a2c" />

### 2. Residual Plot

<img width="893" height="751" alt="Screenshot 2026-06-13 121113" src="https://github.com/user-attachments/assets/05eceacc-3dc6-4fb0-837f-0a69bb59a2fb" />

### 3. Feature Importance Chart

<img width="881" height="732" alt="Screenshot 2026-06-13 121139" src="https://github.com/user-attachments/assets/2c7d6e89-d71e-4135-9eb3-afe0699fec99" />

### 4. Residual Distribution Histogram

<img width="872" height="741" alt="Screenshot 2026-06-13 121202" src="https://github.com/user-attachments/assets/6ea4fb6f-2bef-46f9-8c8f-e01660f63cdb" />

---

## Installation

```bash
git clone https://github.com/yourusername/Temperature-Prediction-Using-Linear-Regression.git

cd Temperature-Prediction-Using-Linear-Regression

pip install -r requirements.txt
```

---

## Running the Project

```bash
jupyter notebook
```

Open:

```text
temperature_prediction.ipynb
```

Run all cells.

---

## Future Enhancements

- Support real-time weather prediction.
- Deploy the model using Flask or FastAPI.
- Integrate weather APIs for live predictions.
- Compare performance with advanced machine learning algorithms such as Random Forest and XGBoost.

---

## Author

**Malaravan R**

Python Full Stack Developer & Machine Learning Enthusiast
