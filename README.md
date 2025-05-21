# SDoH Health Outcome Prediction

This project explores the relationship between **Social Determinants of Health (SDoH)** and health outcomes using machine learning models. It focuses on predicting the **percentage of people in a population who report fair or poor health** based on various SDoH factors.

---

## 📌 What is SDoH?

**Social Determinants of Health (SDoH)** are the non-medical factors that influence health outcomes. These include:

- Income and poverty levels  
- Educational attainment  
- Employment status  
- Access to healthcare  
- Housing stability  
- Community safety  
- Environmental exposures  

### 🏥 Real-life Impact

SDoH account for up to **80% of health outcomes**. People living in disadvantaged social conditions often face:

- Higher risk of chronic diseases  
- Limited access to healthcare services  
- Increased mental health challenges  
- Lower life expectancy  

Understanding these determinants is key to designing better public health policies and interventions.

---

## 🔍 Project Objective

To build machine learning models that predict the **percentage of individuals reporting fair or poor health** based on SDoH data.

---

## 🧠 Models Used

- 🌲 **Random Forest Regressor**  
- ⚡ **XGBoost Regressor**  
- 🔷 **Support Vector Regressor (SVM)**

Each model was trained and evaluated using metrics such as **R² score** and **Root Mean Squared Error (RMSE)** to assess performance.

---

## 📁 Files

- `train_model.py` – Trains and evaluates the models  
- `sdoh_data.csv` – Cleaned dataset of SDoH features and target variable  
- `README.md` – Project overview

---

## 🚀 Future Improvements

- Hyperparameter tuning for better accuracy  
- Feature importance visualization  
- Deployment of the best-performing model via a web app

---

## 📌 Note

This is an academic/educational project and not intended for clinical use.