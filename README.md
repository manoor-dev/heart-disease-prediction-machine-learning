# Heart Disease Prediction using Machine Learning

## Overview

This project predicts the presence of heart disease using machine learning classification algorithms. The workflow includes data preprocessing, exploratory data analysis (EDA), feature selection, model training, performance evaluation, and comparison of multiple Decision Tree configurations with Logistic Regression.

The project demonstrates the complete machine learning pipeline from raw data preprocessing to model evaluation.

---

## Dataset

The project uses the Heart Disease dataset containing patient medical information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- ST Slope
- Number of Major Vessels
- Thalassemia
- Target Variable (Heart Disease)

---

## Project Workflow

### 1. Data Loading

- Import dataset using Pandas
- Display dataset information
- Check dataset dimensions

### 2. Data Exploration

- Dataset summary statistics
- Missing value detection
- Duplicate record detection
- Target class distribution
- Age distribution visualization
- Correlation heatmap
- Outlier visualization using boxplots

### 3. Data Preprocessing

- Remove outliers using the Interquartile Range (IQR) method
- Separate features and target variable
- Standardize numerical features using StandardScaler

### 4. Feature Selection

- Apply SelectKBest with ANOVA F-test
- Select the 10 most relevant features

### 5. Train-Test Split

- 80% Training Data
- 20% Testing Data
- Stratified sampling to preserve class distribution

### 6. Model Development

The following models were implemented:

- Logistic Regression
- Decision Tree Classifier
- Overfitted Decision Tree
- Pruned Decision Tree
- Improved Decision Tree

### 7. Model Evaluation

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

### 8. Model Comparison

Performance of all models was compared to identify the best-performing classifier.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```
Heart-Disease-Prediction/
│
├── heart_disease.csv
├── Heart_Disease_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## Results

The project compares multiple classification models to evaluate their predictive performance on the heart disease dataset.

The comparison demonstrates the impact of:

- Feature scaling
- Feature selection
- Model complexity
- Overfitting
- Underfitting
- Decision tree pruning

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Random Forest Classifier
- XGBoost
- ROC Curve and AUC analysis
- Model deployment using Flask or Streamlit

---

## Author

Mahnoor Sayyed

Business Data Analytics Student

GitHub: https://github.com/manoor-dev
