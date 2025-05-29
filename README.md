# 🧠 Insurance Charges Prediction using Linear Regression

This project focuses on predicting medical insurance charges based on demographic and personal health information using Linear Regression. The dataset includes features such as age, gender, BMI, smoking status, number of children, and region. The goal is to train a regression model that can accurately estimate healthcare costs for individuals.

---

## 📊 Dataset Overview

The dataset (`insurance.csv`) contains 1,338 rows and 7 columns:

- `age`: Age of the primary beneficiary
- `sex`: Gender of the individual (male/female)
- `bmi`: Body mass index
- `children`: Number of children/dependents covered by insurance
- `smoker`: Smoking status (yes/no)
- `region`: Residential region in the US
- `charges`: Individual medical costs billed by health insurance (target variable)

---

## ✅ Project Workflow

### 1. Data Cleaning & Preprocessing
- Checked for missing and duplicate values
- Dropped duplicate records
- Checked for inconsistent labels and outliers

### 2. Exploratory Data Analysis (EDA)
- Statistical summaries and visualizations
- Distribution plots for numerical features
- Count plots for categorical features
- Box plots and correlation heatmap

### 3. Feature Engineering
- Encoded categorical variables (`sex`, `smoker`, `region`)
- Created correlation heatmaps before and after encoding

### 4. Model Training
- Split data into training and test sets (80/20)
- Trained a **Linear Regression** model using `scikit-learn`

### 5. Model Evaluation
- Calculated **R² score**, **MSE**, and **RMSE** on both train and test sets
- Compared predicted vs actual charges for sample inputs

---

## 📈 Model Performance

| Metric              | Training Set | Testing Set |
|---------------------|--------------|-------------|
| R² Score            | 0.73         | 0.81        |
| MSE                 | 37,005,531.73| 35,493,102.61 |
| RMSE                | 6,083.22     | 5,957.61    |

---

## 🔮 Sample Predictions

| Sample | Predicted Charges | Actual Charges |
|--------|-------------------|----------------|
| 1      | 31,316.37         | 39,611.76      |
| 2      | 1,090.56          | 1,837.24       |
| 3      | 12,044.27         | 10,797.34      |

---

## 🛠️ How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/geemethkuruppu/insurance-charges-prediction
cd insurance-charges-prediction

### 2. Install Dependencies
```bash
pip install -r requirements.txt

### 3. Run the Code
```bash
python main.py
