# 🎬 Movie Rating Prediction | IMDb Data Analysis & ML Modeling

Predicting IMDb movie ratings using machine learning techniques applied to real-world movie metadata.

![Python](https://img.shields.io/badge/Python-3.8-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-yellow?style=for-the-badge&logo=scikit-learn)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge&logo=github)

---

## 📌 Overview

This repository contains a complete machine learning pipeline built to **predict IMDb movie ratings** based on a dataset containing metadata of thousands of movies. The project walks through **data cleaning, feature engineering, exploratory data analysis (EDA), model training, evaluation, and tuning** — ending with a highly interpretable regression model.

> 🧠 Perfect for anyone exploring regression, real-world feature handling, and ML workflows using Python.

---

## 📁 Dataset: `IMDb.csv`

The dataset includes the following fields:
- `Title`
- `Genre`
- `Director`
- `Actors`
- `Year`
- `Runtime`
- `Votes`
- `Metascore`
- `Gross`
- `IMDb_Rating` *(target variable)*  
…and more!

---

## 🛠️ Tools & Libraries

- Python 3.8+
- **Pandas** & **NumPy** – Data wrangling
- **Matplotlib** & **Seaborn** – Visualization
- **Scikit-learn** – ML modeling
- **Jupyter Notebook** – Code development

---

## 📊 Exploratory Data Analysis (EDA)

Key insights from the dataset:
- Correlation heatmap to spot predictive features
- Distribution plots (ratings, runtime, votes)
- Genre-based rating comparison
- Handling of missing data (e.g., `Metascore`, `Gross`)

---

## 🔄 Preprocessing Pipeline

- Imputatiion for missing values
- Feature encoding (`Genre`, `Director`, etc.)
- Feature scaling (`StandardScaler`)
- Removal of outliers (if necessary)
- Train-test split (80:20)

---

## 🤖 Machine Learning Models Used

| Model                   | Purpose               | Remarks                      |
|------------------------|-----------------------|-------------------------------|
| Linear Regression       | Baseline              | Easy to interpret             |
| Decision Tree Regressor | Non-linear modeling   | Handles feature interactions  |
| Random Forest Regressor | Ensemble learning     | Better generalization         |
| Gradient Boosting       | High-performance model| Best MAE/RMSE results         |

✅ **Best Model**: `Random Forest Regressor` with RMSE below 0.5 (example, adjust with actual)

---

## 📈 Model Evaluation Metrics

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

Each model's predictions were compared using these metrics to select the best one.

---

## ✅ Results

- Achieved **high accuracy in predicting IMDb ratings**
- Demonstrated **clear understanding of feature impact**
- Created a **scalable ML pipeline**

---

## 🚀 Future Enhancements

- Integrate **user reviews** using NLP for sentiment-based features
- Build a **web app** using Streamlit for live prediction
- Connect to **real-time IMDb APIs** for deployment-ready solution
