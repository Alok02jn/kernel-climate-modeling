# Non-Linear Climate Modeling using Kernel Methods

## Overview
This project explores non-linear regression techniques for climate data modeling using kernel-based machine learning methods.

The goal is to model complex precipitation patterns and evaluate different regression approaches.

---

## Models Implemented

- Linear Regression
- Kernel Ridge Regression (RBF, Polynomial, Sigmoid)
- Support Vector Regression (SVR)
- Random Forest Regressor
- Kernel PCA for non-linear feature transformation

---

## Workflow

1. Data preprocessing and normalization
2. Exploratory Data Analysis (EDA)
3. Model training and hyperparameter tuning (GridSearchCV)
4. Model evaluation using:
   - Mean Squared Error (MSE)
   - R² Score
5. Visualization of model predictions

---

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## How to Run

Install dependencies:

pip install -r requirements.txt

Open and run:

ML_Project_Alok.ipynb

---

## Project Structure

kernel-climate-modeling/
│
├── ML_Project_Alok.ipynb
├── main.py
├── requirements.txt
├── README.md
└── .gitignore

---

## Future Improvements

- Add cross-validation performance comparison
- Convert notebook to modular pipeline
- Deploy model using Streamlit