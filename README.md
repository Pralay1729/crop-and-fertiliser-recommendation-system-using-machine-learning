# edunet
# Crop and Fertilizer Recommendation System using Machine Learning

This repository contains a machine learning-based recommendation system to predict suitable crops and fertilizers based on soil and weather conditions. The system leverages Decision Tree models to provide accurate recommendations for both crops and fertilizers.

---
│── Crops_recommendation_system.csv # Dataset for crop recommendation
│── Fertilizer_recommendation.ipynb # Jupyter Notebook for fertilizer recommendation model
│── README.md # Project documentation
│── crop_model.sav # Trained Decision Tree model for crop recommendation
│── crop_scaler.sav # Scaler used for crop model
│── crops_recommendation_system.ipynb # Jupyter Notebook for crop recommendation model
│── fertilizer_model.sav # Trained Decision Tree model for fertilizer recommendation
│── fertilizer_scaler.sav # Scaler used for fertilizer model
│── .gitignore # Hides my_venv package and other unnecessary files


---

## ✅ **Objective:**

- Develop a prediction system that recommends the most suitable crop and fertilizer based on input features like **temperature, humidity, soil type, pH, and N-P-K (Nitrogen, Phosphorus, Potassium) levels**.
- Utilize a **Decision Tree model** to predict the crop and fertilizer recommendations.

---

## 🛠️ **Technologies Used:**

- **Python 3.13**
- **Scikit-Learn** - for Decision Tree implementation
- **Pandas & NumPy** - for data manipulation
- **Matplotlib & Seaborn** - for data visualization
- **Jupyter Notebook** - for interactive model development

---

## 📦 **Dependencies:**

Install the required libraries using:

```bash

## 📌 **Implementation Details:**
1. Crop Recommendation System:
Model: Decision Tree Classifier

Input Features: N, P, K, Temperature, Humidity, pH, Rainfall

Output: Predicted crop based on soil and weather data

Model File: crop_model.sav

Scaler: crop_scaler.sav

2. Fertilizer Recommendation System:
Model: Decision Tree Classifier

Input Features: N, P, K, pH, Soil Type

Output: Recommended fertilizer type

Model File: fertilizer_model.sav

Scaler: fertilizer_scaler.sav

