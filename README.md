# 🚢 Titanic Survival Prediction

A machine learning project to predict passenger survival on the Titanic using classification algorithms.

---

## 📋 Project Overview

| Item | Detail |
|---|---|
| Dataset | [Titanic - Kaggle](https://www.kaggle.com/c/titanic) |
| Problem Type | Binary Classification |
| Best Model | Random Forest |
| Accuracy | [0.82] |

---

## 📊 Key Insights from EDA

- Female passengers had a significantly higher survival rate **(74% vs 19%)**
- First class passengers survived more than other classes **(63%)**
- Children under 16 were prioritized during evacuation **(59%)**
- **Pclass** and **Sex** are the most negatively and positively correlated features with survival

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data manipulation
- **NumPy** — numerical computation
- **Matplotlib & Seaborn** — visualization
- **Scikit-learn** — machine learning

---

## ⚙️ Preprocessing Steps

- Dropped irrelevant columns: `Name`, `Ticket`, `PassengerId`, `Cabin`
- Filled missing `Age` with median
- Filled missing `Embarked` with mode
- Label Encoding for `Sex` and `Embarked`
- StandardScaler for numeric feature normalization

---

## 🤖 Models Compared

| Model | Train Accuracy | Test Accuracy |
|---|---|---|
| Logistic Regression | [0.8006] | [0.8045] |
| Decision Tree | [0.8497] | [0.7989] |
| Random Forest | [0.8567] | [0.8156] |

---