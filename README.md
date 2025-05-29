# 🚢 Titanic Survival Prediction - Machine Learning Project

This project aims to predict passenger survival on the Titanic using classic machine learning techniques. It is based on the [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/overview), one of the most popular beginner datasets for binary classification problems.

## 📊 Overview

Using data such as age, gender, ticket class, and fare, we built predictive models to determine whether a passenger survived the Titanic disaster. The project walks through the entire data science pipeline — from cleaning the data to building and evaluating machine learning models.

---

## 📁 Project Structure

- `sandhya-titanic-project.ipynb`: Main Jupyter Notebook containing all the code, visualizations, and explanations.
- `README.md`: Project overview and instructions (this file).
- `requirements.txt`: (Optional) Python dependencies required to run the notebook.

---

## 🔍 Key Steps

### 1. Data Preprocessing
- Dropped irrelevant features (like `Cabin`, `Ticket`, and `Name`)
- Filled missing values using statistical imputation (e.g., median age)
- Encoded categorical features (`Sex`, `Embarked`) using Label Encoding

### 2. Exploratory Data Analysis (EDA)
- Plotted survival distributions
- Analyzed feature correlations using heatmaps
- Visualized feature importance from Decision Trees

### 3. Modeling
- **Logistic Regression** for baseline binary classification
- **Decision Tree Classifier** for model interpretability and visualization
- **Cross-Validation** used for robust model evaluation

### 4. Evaluation
- Accuracy scores reported using cross-validation
- Feature importance plotted for Decision Tree
- Confusion matrix and accuracy metrics used to evaluate performance

---

## ✅ Results

- **Decision Tree Accuracy (CV):** ~78–80%
- Most important features: `Sex`, `Fare`, `Pclass`
- Strong baseline performance with room for improvement using ensemble methods

---

## 🚀 Next Steps

- Add **Random Forest** or **XGBoost** for better performance
- Perform **Hyperparameter Tuning** using GridSearchCV
- Deploy using **Streamlit** or **Flask**
- Track experiments with tools like MLflow or Weights & Biases

---

## 🛠️ How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
