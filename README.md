# Epilepsy_prediction_ml_model

# Epilepsy Type Prediction using Machine Learning

## Overview

This project predicts the type of epilepsy using patient clinical information. Multiple machine learning models were trained and compared to identify the best-performing classifier.

## Dataset

- Training Dataset: `train_clean.csv`
- Testing Dataset: `test_clean.csv`
- Training Samples: 20,000
- Testing Samples: 4,500
- Features: 33
- Target: `Target/Epilepsy Type`

## Features

- Age
- Gender
- Weight
- Height
- BMI
- Seizure Frequency
- Seizure Duration
- EEG Results
- MRI Findings
- Family History
- Medication Response
- Other clinical features

## Data Preprocessing

- Removed duplicate records
- Standardized categorical values
- Converted data types
- Removed invalid records
- Created BMI feature
- One-Hot Encoding for categorical features
- Standard Scaling for numerical features

## Models Trained

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Joblib

## Project Structure

```
Epilepsy-Prediction/
│── data/
│── models/
│── notebooks/
│── src/
│── train_clean.csv
│── test_clean.csv
│── requirements.txt
│── README.md
```

## Run the Project

```bash
pip install -r requirements.txt
python train.py
```

## Future Improvements

- Hyperparameter tuning
- SHAP explainability
- Streamlit dashboard
- FastAPI deployment
- Prediction history

## Author

Sandeep Singh
