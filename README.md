# Predictive Modelling for Stock Price Forecasting  
**Integrating Linear and Deep Learning Approaches with Ensemble Techniques**

---

## 🧩 Summary  
This project develops a **hybrid predictive modelling framework** for stock price forecasting by integrating linear models and deep learning architectures within a **stacking ensemble structure**. Using **Apple Inc. (AAPL)** stock data, the study compares **Linear Regression** and **LSTM** models, optimizes them, and then combines their predictive strengths using **Decision Tree** and **XGBoost** meta-learners to achieve improved forecasting accuracy and robustness.

---

## 🎯 Objectives  
- Build baseline models using Linear Regression and LSTM  
- Tune hyperparameters of LSTM for better performance  
- Combine models using ensemble stacking  
- Evaluate results using MSE and RMSE metrics  

---

## 📊 Key Results  

| Model | RMSE | MAE | Notes |
|:------|:------:|:------:|:------|
| Linear Regression | 2.43 | — | Baseline |
| LSTM (initial) | 9.57 | 6.33 | Sequential learning |
| Tuned LSTM | 6.97 | 4.96 | Improved after tuning |
| Decision Tree Ensemble | 2.92 | 2.04 | Better than base models |
| **XGBoost Ensemble** | **2.20** | **1.43** | Best performing model |

---

## ⚙️ Requirements  
Install dependencies:
```bash
pip install -r requirements.txt

