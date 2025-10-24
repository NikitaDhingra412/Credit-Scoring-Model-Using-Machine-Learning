# Credit Scoring Model Using Machine Learning

## Overview

This project implements a credit risk scoring model in Python to predict the likelihood of loan default. It leverages machine learning techniques to analyze borrower information and generate insights for lending decisions. The workflow includes data preprocessing, feature engineering, exploratory data analysis (EDA), and model development.

## Key Features

* **Data Preprocessing:** Handle missing values, remove duplicates, and manage outliers.
* **Feature Engineering:** Create meaningful features such as age groups, income groups, and loan amount categories.
* **Exploratory Data Analysis:** Visualize distributions, correlations, and trends for deeper understanding.
* **Machine Learning Models:** Logistic Regression, Decision Tree, Random Forest, and XGBoost.
* **Hyperparameter Tuning:** Optimize XGBoost using RandomizedSearchCV.
* **Model Evaluation:** Metrics include Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix, and ROC Curve.
* **Feature Importance:** Identify top features contributing to predictions.
* **Model Saving:** Persist trained model using joblib for future predictions.

## Usage

1. Clone the repository:

   ```
   git clone <repository_url>
   ```
2. Install required packages:

   ```
   pip install -r requirements.txt
   ```
3. Open `credit_scoring.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook to reproduce the analysis and model training.
5. The trained model is saved as `best_xgb_model.pkl` for prediction on new data.

## Project Structure

* `credit_scoring.ipynb` – Full workflow of the project.
* `credit_risk_dataset.csv` – Dataset used (share only if anonymized).
* `best_xgb_model.pkl` – Saved XGBoost model.
* `requirements.txt` – Python dependencies.
* `.gitignore` – Files and folders excluded from GitHub.

## Future Improvements

* Deploy the model as a web application or REST API for real-time predictions.
* Explore additional machine learning algorithms and ensemble methods.
* Enhance feature engineering and incorporate external data for improved accuracy.

---
