# Diabetes Prediction Model 

This project predicts whether a person has diabetes using the Pima Indian Diabetes Dataset. It compares the performance of **Logistic Regression** and **Random Forest Classifier** models.

##  Dataset
- **Source**: Pima Indian Diabetes Dataset (UCI Machine Learning Repository)

##  Project Steps
1. Data Cleaning & EDA (Exploratory Data Analysis)
2. Feature Scaling (for Logistic Regression)
3. Model Training: 
   - Logistic Regression
   - Random Forest Classifier
4. Evaluation using:
   - Precision
   - Recall
   - Classification Report

##  Results
| Model              | Precision | Recall |
|-------------------|-----------|--------|
| Logistic Regression | 0.65      | 0.67   |
| Random Forest       | 0.61      | 0.62   |

##  Libraries Used
- pandas, numpy, matplotlib, seaborn
- scikit-learn (LogisticRegression, RandomForestClassifier, metrics)

##  Goal
Build an interpretable model for medical diagnosis and compare it with a powerful tree-based ensemble method.

