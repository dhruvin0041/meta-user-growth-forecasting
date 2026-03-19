# 🚀 Meta-Style User Growth Forecasting System

## 📌 Overview

This project builds a **production-grade machine learning pipeline** to forecast Daily Active Users (DAU), inspired by real-world systems used at large-scale platforms like Meta.

It combines **time-series modeling, advanced feature engineering, and explainability techniques** to predict user growth and uncover key drivers behind engagement.

---

## 🎯 Objectives

* Predict Daily Active Users (DAU)
* Forecast user growth for multiple horizons (t+1, t+7, t+30)
* Identify key drivers of engagement and retention
* Build a scalable and explainable ML system

---

## 🧠 Key Features

### 🔹 Multi-Horizon Forecasting

* Direct prediction for multiple future horizons (1, 7, 30 days)
* Eliminates recursive error accumulation
* Improves stability and reliability

---

### 🔹 Advanced Feature Engineering

* Lag features (short-term, weekly, monthly)
* Rolling statistics (mean, std, max, min)
* Momentum & trend features
* Behavioral signals (engagement, ads)
* Interaction features (nonlinear relationships)
* Prophet-based trend & seasonality

---

### 🔹 Machine Learning Models

* **LightGBM** → captures nonlinear user behavior
* **Prophet** → extracts trend and seasonality
* Hyperparameter tuning with **RandomizedSearchCV**

---

### 🔹 Explainability (SHAP)

* Global feature importance
* Local prediction explanations
* Understand **why the model predicts growth/decline**

---

## 📊 Results

| Metric   | Value         |
| -------- | ------------- |
| Accuracy | ~0.84 → ~0.90 |
| MAPE     | ~10–16%       |
| RMSE     | ~4–6          |

---

## 🔍 Key Insights

* User growth is primarily driven by:

  * Recent activity (lag features)
  * Engagement per user
  * Trend strength
  * Seasonality patterns

* Combining statistical + ML models improves performance and stability

* Explainability (SHAP) helps translate model output into business insights

---

## 📂 Dataset

Due to GitHub file size limitations (~30MB), the full dataset is hosted externally:

🔗 **Download Full Dataset:** https://drive.google.com/file/d/1LdQ3lCBlccjAFyTymPzonpzQN7HEx7f3/view?usp=sharing

---

## 📈 Tech Stack

* Python
* Pandas, NumPy
* LightGBM
* Prophet
* SHAP
* Scikit-learn
* Matplotlib

---

## 📂 Project Structure

```
meta-user-growth-forecasting/
│
├── User_Growth.ipynb
├── README.md
```

---

## 🚀 Future Improvements

* Transformer-based forecasting (TFT)
* Real-time prediction pipeline
* API deployment (FastAPI / Flask)
* Interactive dashboard (Streamlit)

---

## 🧠 Key Learnings

* Time-series forecasting requires both **temporal + behavioral features**
* Multi-horizon models outperform recursive forecasting
* Feature engineering has the biggest impact on performance
* Explainability is critical for real-world ML adoption

---

## 🤝 Connect

If you found this project useful or have feedback, feel free to connect!

⭐ If you like this project, consider giving it a star!
