
# 📘 Laptop Price Prediction (Machine Learning)

This project predicts laptop prices based on hardware specifications and category features using various machine learning models. It includes data preprocessing, exploratory analysis, linear and polynomial regression, and regularization techniques to improve model performance.

### 🚀 Project Summary

The notebook explores:
-Data Cleaning & Feature Selection
-Simple Linear Regression using CPU frequency
-Polynomial Regression (degree 2–20) for overfitting analysis
-Ridge Regression with manual alpha tuning
-GridSearchCV for optimal hyperparameters
-Improved Pipeline using:
       StandardScaler
       OneHotEncoder
       ColumnTransformer
       Ridge regressor

The final pipeline ensures proper encoding, scaling, and reliable cross-validation.

### 📂 Dataset

File: LaptopPricing-Dataset-3.csv
Target: Price
Key Features:
CPU_frequency, RAM_GB, Storage_GB_SSD, CPU_core
GPU, OS, Category
Unnecessary columns like Unnamed: 0 were removed.

### 📈 Modeling & Evaluation

Models evaluated using:
-R² Score
-RMSE
-Cross-validated RMSE
Regularization via Ridge reduced overfitting, and GridSearchCV identified the best alpha.

### 🔧 Tech Stack

-Python
-Scikit-learn
-Pandas, NumPy
-Matplotlib, Seaborn
-Jupyter Notebook

### 📊 Future Improvements

-Add Random Forest / XGBoost for comparison
-Deploy as a web app (Flask or Streamlit)
-Add feature importance analysis
