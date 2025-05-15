# Sales-profit-Analysis
# 📊 Sales & Profit Analysis – End-to-End Data Science Project

This project is an end-to-end data analysis and modeling exercise using a public Sales dataset from Kaggle. It includes data preprocessing, exploratory analysis, feature engineering, predictive modeling, and interactive dashboarding using Power BI.

---

## 🚀 Project Objectives

- Understand how different factors (like discount, segment, region) affect **Sales** and **Profit**
- Build a predictive model to estimate **Sales**
- Visualize key business KPIs using **Power BI**

---

## 🧰 Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost)
- **Google Colab** for development
- **Power BI** for interactive dashboards
- **Jupyter Notebook (.ipynb)** for analysis and modeling
- **GitHub** for version control

---


---

## 🧠 Key Insights from EDA

- **High Discounts** often reduce profits even if they increase sales.
- **Technology category** generated the highest profit margin overall.
- **West region** was the strongest performer in terms of sales.
- **Home Office** segment had lower average sales compared to Corporate and Consumer.

---

## 🤖 Model Building

I tested multiple regression models:

1. **Random Forest Regressor**: Initially used but showed signs of overfitting (Training R² = 0.94 vs CV R² = 0.59)
2. **XGBoost Regressor**: Used with feature engineering and log transformation of sales to improve generalization. Final CV R² ≈ 0.89+

### ✨ Feature Engineering

- **Price per Unit** = Sales / Quantity
- **Profit Margin** = Profit / Sales
- **Is Discounted** = Boolean indicating if discount > 0

---

## 📈 Power BI Dashboard Features

- KPIs: Total Sales, Profit, Discount, Quantity
- Slicers: **Segment**, **State**, **Year**
- Charts:
  - Sales vs Profit by Category & Sub-Category
  - Regional sales trends
  - Top 3 and Bottom 3 cities by profit



---

## 🔗 Dataset Source

Publicly available on Kaggle – [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## 📌 Author

**Logien Mekki**  
Master's in Data Science | Data Science | Business Intelligence | AI  
[LinkedIn Profile](https://www.linkedin.com/in/logien-mekki)  


