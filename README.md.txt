# Insurance Charges Prediction

This project performs data cleaning, exploratory data analysis (EDA), feature engineering, linear regression modeling, and evaluation on a medical cost dataset (`insurance.csv`).

## Dataset
The dataset includes information like age, sex, BMI, number of children, smoking status, region, and charges (medical insurance cost).

## Steps:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Model Training with Linear Regression
- Model Evaluation (R², MSE, RMSE)
- Predictive System with Sample Inputs

## Model Results
- **Training R²:** 0.73
- **Testing R²:** 0.81
- **Testing RMSE:** 5957.61

## Sample Predictions
| Sample | Predicted | Actual   |
| ------ | --------- | -------- |
| 1      | 31316.37  | 39611.76 |
| 2      | 1090.56   | 1837.24  |
| 3      | 12044.27  | 10797.34 |



## How to Run
```bash
pip install -r requirements.txt
python main.py
