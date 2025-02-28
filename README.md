# Air Quality Index Prediction Model

## Project Overview
This project predicts the **Air Quality Index (AQI)** using machine learning techniques. The model uses environmental features such as **PM2.5, PM10, NO2, CO, O3, SO2, Temperature, Humidity, and Wind Speed** to predict AQI levels.

## Dataset
The dataset contains:
- Air pollution levels (PM2.5, PM10, NO2, CO, O3, SO2)
- Weather conditions (Temperature, Humidity, Wind Speed)
- Air Quality Index (AQI - Target Variable)

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How It Works
1. **Data Preprocessing**: Missing values are filled with the mean of the column.
2. **Feature Selection**: Important environmental features are selected.
3. **Model Training**: The Random Forest Regressor model is used to train the dataset.
4. **Prediction**: The model predicts AQI values.
5. **Evaluation**: The model is evaluated using **Mean Squared Error (MSE)** and **R-Squared Score (R2)**.

## Results
- The model provides accurate predictions of AQI values.
- Feature importance is visualized to show which factors affect air quality the most.
