# Student Performance Prediction using Logistic Regression

## 📌 Project Overview

This project uses **Machine Learning** to predict whether a student is likely to **Pass or Fail** based on academic, demographic, and behavioral factors.

A **Logistic Regression** classification model is used to perform the prediction.

## 🎯 Objective

The main objective of this project is to build an end-to-end binary classification model that can predict student performance and identify factors that may influence the prediction.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Colab Notebook

## 📊 Dataset

The dataset contains information about students, including features related to:

* Demographics
* Family background
* Study habits
* Academic performance
* Absences
* Social and behavioral factors

The target variable is:

* `0` → Fail
* `1` → Pass

## 🔄 Machine Learning Workflow

1. Data loading
2. Data understanding and exploration
3. Data preprocessing
4. Separation of features (`X`) and target (`y`)
5. Train-test split
6. Categorical feature encoding using `OneHotEncoder`
7. Numerical feature scaling using `StandardScaler`
8. Logistic Regression model training
9. Prediction
10. Model evaluation
11. Confusion matrix analysis
12. Precision, Recall and F1-score evaluation
13. Coefficient analysis
14. Probability prediction using `predict_proba()`
15. Cross-validation
16. Hyperparameter tuning

## 🤖 Model

The project uses **Logistic Regression**, a supervised machine learning algorithm used for binary classification.

The model predicts the probability of a student belonging to the `Pass` class and then assigns the final class based on the decision threshold.

## 📈 Results

The initial model achieved approximately **65.82% accuracy**.

After scaling and hyperparameter tuning, the model achieved approximately **69% accuracy** on the test set.

The model was also evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* 5-Fold Cross-Validation

## 🔍 Feature Analysis

Logistic Regression coefficients were analyzed to understand how different features influence the model's prediction.

Positive coefficients push the prediction toward the **Pass** class, while negative coefficients push it toward the **Fail** class, keeping other features constant.

## 📁 Project Structure

```text
Student-Performance-Prediction/
│
├── student_performance.ipynb
├── student_pass_prediction_model.pkl
├── student-mat.csv
└── README.md
```

## 🚀 Future Improvements

* Experiment with other classification algorithms such as Decision Tree, Random Forest and XGBoost.
* Perform more extensive hyperparameter tuning.
* Improve feature selection.
* Compare multiple models using cross-validation.
* Deploy the final model as a web application using Streamlit or an API.

## 👩‍💻 Author

**Nishtha Nigam**

B.Tech CSE (AI-ML)
