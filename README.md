# 🌧️ Rainfall Prediction using Machine Learning

This project aims to predict rainfall based on meteorological variables such as temperature, dewpoint, humidity, cloud cover, sunshine, and wind speed. Multiple machine learning models were trained and evaluated to identify the most suitable algorithm for this classification task.

---

## 📂 Project Structure


---

## 🎯 Project Objectives

- Perform data cleaning and preprocessing
- Understand patterns in weather parameters related to rainfall
- Conduct Exploratory Data Analysis (EDA)
- Train multiple ML models for classification
- Evaluate performance using industry metrics
- Select the best-performing model

---

## 🧠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Scikit-Learn**
- **XGBoost**

---

## 🔍 Exploratory Data Analysis Insights

Rainfall is typically associated with:

- Lower maximum temperature
- Higher dewpoint
- Higher humidity
- Increased cloud presence
- Lower sunshine duration
- Slightly higher wind speed

Outliers were detected but retained due to limited data points.

---

## 🤖 Machine Learning Models Trained

- Logistic Regression
- Support Vector Classifier (SVC)
- XGBoost Classifier

---

## 📊 Model Evaluation (Highlights)

- **Logistic Regression** achieved the most stable and balanced results
- **SVC** performed closely and showed good generalization
- **XGBoost** showed signs of overfitting and requires tuning

**AUC Scores Comparison:**

| Model                | AUC Score |
|---------------------|-----------|
| Logistic Regression | 0.90      |
| SVC                 | 0.89      |
| XGBoost             | 0.84      |

✅ **Final Model Choice:** Logistic Regression

--
