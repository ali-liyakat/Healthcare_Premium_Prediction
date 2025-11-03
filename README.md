# 🏥 Healthcare Premium Prediction

A machine-learning project to predict individual health-insurance premiums based on personal and lifestyle factors. The project includes full end-to-end ML workflow — data cleaning, feature engineering, model building, evaluation, and live deployment using Streamlit.

---

## 📊 Project Workflow

1. **Data Cleaning & Preprocessing**
   - Handled missing/outlier values
   - Used Label Encoding, One-Hot Encoding
   - Applied Feature Scaling and Transformation

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature impacts using correlation heatmaps, distribution plots, boxplots, etc.
   - Derived useful feature insights for ML models

3. **Model Training & Evaluation**
   - Trained multiple models: Linear Regression, Ridge Regression, XGBoost
   - Used RandomizedSearchCV for hyperparameter tuning
   - Performed Error Analysis (MAE, RMSE, R²)
   - Also applied **model segmentation** (separate models for different age groups)

4. **Deployment**
   - Saved best model using `joblib`
   - Built and deployed a Streamlit web app for real-time predictions  
   - ✅ **Live App:** [Click here to try it]([(https://healthcare-insurance-predictor.streamlit.app/)]
))

---

## 🧪 Tech Stack

- **Python**
- **Scikit-learn**, **XGBoost**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Streamlit**
- **Joblib**

---
