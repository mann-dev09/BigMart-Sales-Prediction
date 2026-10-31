# BigMart-Sales-Prediction
BigMart sales prediction using Gamma Regression, EDA, feature engineering and cross-validation.
# BigMart Sales Prediction

## Advanced Modelling & Business Analytics

### Project Overview
This project focuses on predicting Item Outlet Sales using machine learning and statistical modelling techniques.

The project uses the BigMart dataset to understand sales patterns, engineer meaningful features, train a Gamma Regression model, and generate sales predictions.

### Objectives
- Explore and understand the BigMart dataset through Exploratory Data Analysis (EDA).
- Identify useful patterns and relationships in the data.
- Perform feature engineering.
- Develop a Gamma Regression model.
- Evaluate model performance using cross-validation.
- Generate predicted sales for the test dataset.

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab
- Jupyter Notebook

### Machine Learning Approach
**Model:** Gamma Regression

**Feature Engineering:**
- Outlet one-hot encoding.
- Log transformation of Item MRP.
- Store-specific price effects.
- Spline transformation of product identifier numbers.

### Model Evaluation
The project evaluates model performance using:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score
- Five-fold Cross-Validation

### Project Structure
```text
BigMart-Sales-Prediction/
│
├── BigMart_Gamma.ipynb
├── bigmart_gamma.py
├── gamma_submission.csv
└── README.md
```

### Dataset
The project requires the following input files:
- train.csv
- test.csv
- sample_submission.csv

These datasets should be placed in the `data/` folder when running the Python implementation.

### Final Output
The model generates predicted Item Outlet Sales and exports the results as a CSV submission file.

---
**Project Domain:** Business Analytics & Machine Learning  
**Model:** Gamma Regression  
**Purpose:** Retail Sales Prediction
