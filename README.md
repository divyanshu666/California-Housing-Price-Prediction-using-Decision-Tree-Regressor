# 🏡 California Housing Price Prediction using Decision Tree Regressor

This project applies a **Decision Tree Regressor** to the **California Housing Dataset** to predict median house values based on features such as income level, population, and location. It also includes **hyperparameter tuning using GridSearchCV**, achieving an **R² score of 0.52** on the test set.

---

## 📊 Overview

- **Dataset**: California Housing Dataset (`sklearn.datasets`)
- **Model**: `DecisionTreeRegressor`
- **Tuning**: `GridSearchCV` with 5-fold cross-validation
- **Metric**: R² Score
- **Final R² Score**: **0.52**

---

## 🧠 Objective

Predict the median house price in various California districts based on socioeconomic and geographical features.

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

---

## 🚀 Workflow

1. **Import Dataset**
   - Used `fetch_california_housing()` from sklearn.
2. **Preprocessing**
   - Feature scaling, handling input/output split.
3. **Model Training**
   - Applied `DecisionTreeRegressor`.
4. **Hyperparameter Tuning**
   - Tuned parameters like `max_depth`, `min_samples_split` using `GridSearchCV`.
5. **Evaluation**
   - Evaluated with R² score.
   - Final score: **0.52**.

---

