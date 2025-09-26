# 🚗 Car Price Prediction  
This project is part of the course **SF2935 Modern Methods of Statistical Learning**.  
It builds and explains machine learning models for **predicting car prices** based on historical sales data.  
The workflow includes data preprocessing, an XGBoost model, and a Neural Network model, with SHAP explainability to highlight global and local feature importance.  
   

## Project Structure
```  
├── car_sales_data.csv # Raw dataset
├── clean_df.csv # Preprocessed / cleaned dataset
├── data_mgmt.ipynb # Data cleaning & feature engineering
├── NN_model.joblib # Trained Neural Network model
├── NN.ipynb # Neural Network training notebook
├── XGB_model.joblib # Trained XGBoost model
├── XGB.ipynb # XGBoost training notebook
```


## Features  
- **Data Preprocessing**: Cleaning, encoding, and preparing raw car sales data.  
- **Modeling**:  
  - **XGBoost** model for structured data performance.  
  - **Neural Network (NN)** model for deep learning experimentation.  
- **Explainability**: SHAP values to interpret model predictions.  
- **Reproducibility**: All steps documented in Jupyter notebooks.  


## Authors  
- Alexander Jenee
- Tasin Biswas
- Georgios Hanna
- Gorgis Abdow  