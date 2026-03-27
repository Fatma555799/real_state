# Real Estate Price Prediction & Interpretation using Random Forest

## 📋 Project Description

This project focuses on predicting **listPrice** (real estate prices) using tree-based machine learning models, with a strong emphasis on model interpretation and feature importance.

The analysis includes:
- Data preprocessing and handling of categorical variables
- Custom encoding functions (`train_cats`, `proc_df`)
- Training a **Random Forest Regressor**
- Model evaluation using R², MSE, and RMSE
- Feature importance analysis
- Visualization of price distribution and model predictions

## 🛠️ Technologies & Libraries

- **pandas** & **numpy**
- **scikit-learn** (RandomForestRegressor)
- **seaborn** & **matplotlib**
- Custom helper functions for categorical encoding and scoring

## 📁 Files

- `interpretation_real_state.ipynb` → Main Jupyter Notebook
-  https://www.kaggle.com/datasets/kanchana1990/new-hampshire-real-estate-data-2026?select=new_hampshire_real_estate_2026.csv → Real estate dataset
## 🚀 How to Run

1. Extract the dataset:
   ```bash
   unzip archive.zip
Install required packages:Bashpip install pandas numpy scikit-learn seaborn matplotlib
Launch the notebook:Bashjupyter notebook interpretation_real_state.ipynb

📊 Main Steps

Loading and exploring the real estate dataset
Handling missing values
Converting object columns to ordered categorical variables
Custom data processing with proc_df() and target transformation (np.log)
Training Random Forest Regressor with Out-of-Bag (OOB) scoring
Feature importance ranking
Visualization of price distribution (listPrice)
Analysis of prediction uncertainty per property type

🔍 Key Insights

sqft and baths are the most important features for predicting price
Log transformation was applied to the target variable (listPrice)
Feature importance extracted from the Random Forest model
Price distribution and model behavior analyzed across different property types (condo, single_family, etc.)
