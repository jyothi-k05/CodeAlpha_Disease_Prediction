# codealpha_medical_model_comparison

This Streamlit application compares the performance of four different machine learning models (Logistic Regression, SVM, Random Forest, and XGBoost) on three different medical datasets:

- Breast Cancer
- Heart Disease
- Diabetes

## How It Works

- Datasets are loaded from local CSV files.
- Each dataset is preprocessed, scaled, and split into training and testing sets.
- Four machine learning models are trained on each dataset.
- Model accuracy is evaluated and compared using bar charts and tables.

## Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

## Requirements

Install the dependencies using:

```
pip install -r requirements.txt
```

## Run the App

```
streamlit run app.py
```

Ensure that your data files are in the following locations:

```
data/breast_cancer/wdbc.data
data/heart/processed.cleveland.data
data/diabetes/diabetes.csv
```

## Author

Submitted for CodeAlpha Internship Program.