# 🚗 Car Price Prediction with Machine Learning

## 📌 Objective  
To develop a machine learning model that accurately predicts **used car prices** based on multiple influencing factors such as brand, fuel type, transmission, mileage, ownership, and car age.  
This project aims to explore the factors affecting car prices and apply predictive modeling to assist in pricing decisions in the automotive market.  

---

## 🔎 Steps Performed  
1. **Dataset Preparation**  
   - Loaded `car data.csv` dataset (from Kaggle).  
   - Key columns: `Car_Name`, `Year`, `Selling_Price`, `Present_Price`, `Driven_kms`, `Fuel_Type`, `Selling_type`, `Transmission`, `Owner`.  

2. **Data Preprocessing**  
   - Cleaned dataset, handled categorical variables, and transformed features.  
   - Created new features like **car age**.  
   - Checked for outliers and correlations.  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized relationships between features and car prices.  
   - Key insights:  
     - **Automatic transmission cars** generally priced higher than manual.  
     - **Diesel cars** have higher resale prices compared to petrol and CNG.  
     - **First-owner cars** fetch higher prices than second or third-owner cars.  
     - **Driven kilometers** negatively correlate with selling price.  
     - **Newer cars and higher present prices** strongly influence selling price.  

4. **Modeling & Evaluation**  
   - Trained and evaluated multiple machine learning models: **Linear Regression, Decision Tree, Random Forest, XGBoost, Gradient Boosting**.  
   - Used **R² Score, MAE, MSE, and RMSE** for performance evaluation.  

---

## 🛠️ Tools & Libraries  
- **Python, Jupyter Notebook**  
- **pandas, numpy** (data preprocessing)  
- **matplotlib, seaborn** (visualization)  
- **scikit-learn, XGBoost** (model building & evaluation)  

---

## 📈 Results  

| Model                     | R² Score | MAE     | MSE     | RMSE    |
|---------------------------|----------|---------|---------|---------|
| Gradient Boosting Regressor | 0.9676   | 0.4202  | 0.3847  | 0.6202  |
| Random Forest Regressor     | 0.9504   | 0.4931  | 0.5888  | 0.7673  |
| Decision Tree Regressor     | 0.9432   | 0.4899  | 0.6741  | 0.8210  |
| XGB Regressor               | 0.9277   | 0.5352  | 0.8583  | 0.9264  |
| Linear Regression           | 0.8730   | 0.9378  | 1.5070  | 1.2276  |

✅ **Best Model:** **Gradient Boosting Regressor** with **R² = 0.9676** and lowest error metrics.  

---

## 🎯 Outcome  
- Successfully built a robust car price prediction model.  
- **Gradient Boosting Regressor** proved to be the most accurate, achieving **96.7% R² Score**.  
- Extracted valuable insights on how features like **fuel type, ownership, transmission, car age, and driven kilometers** influence car pricing.  
- Demonstrated the importance of **feature engineering** and **model comparison** in machine learning projects.  

---

👨‍💻 Developed as part of the **Data Science Internship at Oasis Infobyte**  
