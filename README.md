# House Price Prediction
A machine learning project that predicts house prices using the California Housing dataset.

## Overview
This project uses machine learning to predict the median house value based on housing and demographic features.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Machine Learning Workflow
- Data loading and preprocessing
- Stratified train-test split
- Handling missing values
- Feature scaling using StandardScaler
- Categorical encoding using OneHotEncoder
- Preprocessing using Pipeline and ColumnTransformer
- Random Forest Regression
- Model evaluation using MAE, RMSE, and R²
- Saving the trained model using Joblib

.... Model
The project uses a **Random Forest Regressor** to predict `median_house_value`.

## Evaluation
The model is evaluated using:

- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**

These metrics are used to measure the accuracy and performance of the model.

## Dataset
The project uses the California Housing dataset.

Target variable:
`median_house_value`

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
