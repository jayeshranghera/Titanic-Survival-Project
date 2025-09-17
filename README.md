# Titanic Survival Prediction 

This project predicts the survival of passengers on the Titanic using machine learning models. It is based on the famous **Kaggle Titanic dataset** and demonstrates 
the full workflow of a data science project — from data preprocessing to model evaluation.

---

## Project Overview

The goal is to build predictive models that can classify whether a passenger survived or not, based on features like class, age, sex, fare, and number of relatives onboard.

---

## Steps Involved

1. Data Loading & Exploration

   * Loaded dataset using Pandas.
   * Performed exploratory data analysis (EDA) with visualizations (Seaborn, Matplotlib).
   * Survival distributions analyzed by gender, class, and age.

2. Data Preprocessing

   * Selected relevant features: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`.
   * Handled missing values (median for `Age`, mode for `Embarked`).
   * Encoded categorical features using one-hot encoding.

3. Model Building

   * Implemented and trained multiple models:

     * K-Nearest Neighbors (KNN)
     * Decision Tree Classifier
     * Random Forest Classifier

4. Model Evaluation

   * Evaluated models using:

     * Accuracy Score
     * Confusion Matrix
     * Classification Report (Precision, Recall, F1)
     * ROC Curve & AUC Score

---

##  Results

* Models compared on accuracy and AUC.
* Random Forest performed best in terms of overall metrics.

---

## Tech Stack

* **Languages/Tools**: Python, Jupyter Notebook
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

##  Author

Developed by Jayesh Ranghera  
