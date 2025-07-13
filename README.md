# Respiratory_Risk_Classification
🫁 Respiratory Risk Classification (3-Class)
This project predicts respiratory health risk (Low, Moderate, High) using real-time AQI data and environmental parameters, powered by an XGBoost classifier trained with SMOTE for class balance.

✅ Highlights
3-class risk prediction:

0: Low Risk

1: Moderate Risk

2: High Risk

Trained on augmented data using SMOTE

Real-time AQI via AQICN API

Deployed on a Streamlit dashboard

Uses StandardScaler for preprocessing

🧠 Features Used
AQI, NO₂, SO₂, O₃

Temperature, Humidity, Wind Speed

Dummy variables for AQI risk levels (low/moderate/high)



🛠️ Model
Algorithm: XGBoost Classifier

Handling Imbalance: SMOTE

Input Scaler: StandardScaler

Output Classes: [0, 1, 2] for increasing risk levels

📈 Output Example
"Predicted Risk: High (2) – Take caution and limit outdoor activities."

