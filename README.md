# Dry Bean Type Classification

## Project Overview

This project uses Machine Learning techniques to automatically classify different types of dry beans based on their physical characteristics.

The goal is to replace manual bean classification with an automated and scalable AI solution that improves accuracy and efficiency in agricultural quality control.

---

## Business Problem

Manual classification of dry beans is time-consuming, labor-intensive, and prone to human errors.

This project develops a machine learning solution capable of identifying bean varieties using features extracted through computer vision systems.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Streamlit
- Joblib

---

## Machine Learning Workflow

### Data Analysis

- Dataset Exploration
- Class Distribution Analysis
- Correlation Analysis
- Feature Visualization

### Data Preprocessing

- Missing Value Handling
- Outlier Detection
- Feature Scaling
- Train-Test Split using Stratified Sampling

### Models Implemented

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors
- Support Vector Machine
- Naive Bayes
- Ensemble Methods

### Advanced Techniques

- Cross Validation
- Hyperparameter Tuning
- Class Imbalance Handling (SMOTE)
- Overfitting Detection

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Results

The models were compared based on training accuracy, testing accuracy, F1 Score, and overfitting behavior.

The best-performing model was selected and deployed for bean type prediction.

---

## Streamlit Application

A Streamlit web application was developed to allow users to input bean characteristics and instantly predict the bean class.

---


## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## Author

Shimanta Nath
