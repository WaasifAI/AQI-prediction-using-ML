# AQI Prediction using Machine Learning

## 📌 Project Overview
This project builds a regression-based Machine Learning model to predict Air Quality Index (AQI) using real-world pollution data. The model analyzes pollutant concentrations such as PM2.5, PM10, NOx, CO, SO2, O3, Benzene, Toluene, and Xylene to estimate AQI values.

The goal is to create a reliable predictive system that can assist in air quality assessment and future scenario analysis.

---

## ⚙️ Project Workflow

1. Data Loading and Exploration  
2. Missing Value Handling (Mean Imputation)  
3. Feature Selection and Target Separation  
4. Train-Test Split (80% Training, 20% Testing)  
5. Feature Scaling using StandardScaler  
6. Model Training:
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
   - XGBoost Regressor  
7. Model Evaluation using:
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Error (RMSE)  
8. Best Model Selection  
9. Future Scenario Predictions  
10. Model and Scaler Saving for Deployment  

---

## 📊 Model Performance

The best-performing model was selected based on highest R² score and lowest prediction error.

Evaluation Metrics Used:
- R² Score (Explained Variance)
- MAE (Average Prediction Error)
- RMSE (Penalizes Larger Errors)

The selected model demonstrates strong predictive capability and reliable generalization on unseen data.

---

## 🔮 Future Prediction Scenarios

The project includes simulated air quality scenarios (Good, Moderate, Poor, Very Poor) to test how pollutant levels affect predicted AQI values.

This demonstrates potential real-world application of the trained model.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-Learn  
- XGBoost  
- Joblib  

---

## 📂 Output Files

- `best_aqi_model.pkl` – Trained regression model  
- `scaler.pkl` – Feature scaling object  
- `aqi_predictions.csv` – Model predictions on test data  

---

## 🚀 How to Run

1. Clone the repository  
2. Install required dependencies  
3. Run the main notebook or Python script  

