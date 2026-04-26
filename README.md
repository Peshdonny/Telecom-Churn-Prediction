# Telecom Customer Churn Prediction

## Project Overview
This project applies machine learning techniques to predict telecom customer churn using two approved datasets:

- Iranian Churn Dataset  
- Bulgarian Telecom Customer Churn Dataset

The objective was to compare multiple models and identify the best approach for churn prediction.

---

## Business Problem

Customer churn is a major challenge in the telecom industry because losing customers reduces revenue and increases acquisition costs. Predicting churn early helps telecom companies improve retention strategies.

---

## Datasets Used

### 1. Iranian Churn Dataset
- 3,150 rows
- 14 columns
- Target Variable: `Churn`

### 2. Bulgarian Telecom Dataset
- 8,453 rows
- 14 columns
- Target Variable: `CHURN`

---

## Project Workflow

### Data Preparation
- Missing value handling
- Feature preprocessing
- Scaling
- Train-test split

### Exploratory Data Analysis
- Churn distribution
- Customer value analysis
- Dataset comparison

### Models Applied
- Logistic Regression
- Random Forest
- Neural Network

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Best Model

### Random Forest (Iranian Dataset)

This model achieved the strongest overall performance and was selected as the final churn prediction model.

---

## Key Findings

- The Iranian dataset produced strong predictive performance.
- Random Forest was the best overall model.
- The Bulgarian dataset was more difficult to model.
- Accuracy alone was not enough because of class imbalance.

---

## Repository Files

- `Telecom_churn_project_annotated.ipynb` → Full project notebook  
- `final_model_results.csv` → Final model comparison results  
- `.png files` → Charts used in analysis  
- `.pkl files` → Saved trained model and scaler  

---

## Tools Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

## Author

Project completed as part of a Machine Learning / Data Engineering coursework project.
