# house-price-prediction
# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict house prices using Machine Learning regression models.
The objective is to understand the full ML pipeline: data preprocessing, exploratory data analysis,
feature engineering, model training, evaluation, and prediction on new data.

The project was implemented using **Python**, **scikit-learn**, and **Google Colab**.

---

## 📂 Dataset
- Format: CSV
- Target variable: `price`
- The dataset contains numerical and categorical features describing houses
  (size, location, condition, etc.).

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Google Colab

---

## 🧠 Machine Learning Workflow

1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature selection and encoding  
4. Train / Test split  
5. Feature scaling (StandardScaler)  
6. Model training:
   - Linear Regression
   - Ridge Regression
   - Ridge Regression with Cross-Validation (RidgeCV)
7. Model evaluation using RMSE and R²
8. Prediction on new unseen data

---

## 📊 Models and Results

| Model | RMSE | R² |
|------|------|----|
| Linear Regression | ~517,000 | -1.55 |
| Ridge Regression | ~424,000 | -0.72 |
| RidgeCV + log(price) | **~226,000** | **0.51** |

➡️ The best performance was achieved using **Ridge Regression with Cross-Validation**
and a **log transformation of the target variable**.

---

## 📐 Evaluation Metrics
- **RMSE (Root Mean Squared Error)**: Measures average prediction error in the same unit as price.
- **R² Score**: Indicates how much variance in house prices is explained by the model.

---

## 🔍 Key Learnings
- Importance of Exploratory Data Analysis
- Impact of feature scaling and regularization
- Avoiding data leakage
- Using cross-validation to select hyperparameters
- Transforming skewed target variables

---

## 🚀 Future Improvements
- Test Lasso and ElasticNet
- Try tree-based models (Random Forest, XGBoost)
- Feature importance analysis
- Model deployment using Streamlit

---

## 👨‍💻 Author
**Ahmed Baccari**  
2nd Year Computer Engineering Student  
Machine Learning Enthusiast
