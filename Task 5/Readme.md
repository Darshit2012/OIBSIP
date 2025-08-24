# 📊 Sales Prediction with Machine Learning  

## 📌 Objective  
To develop a machine learning model that predicts **product sales** based on advertising expenditure across TV, Radio, and Newspaper.  
The project aims to analyze the impact of different advertising channels on sales and build a predictive model to assist businesses in **marketing strategy optimization**.  

---

## 🔎 Steps Performed  
1. **Dataset Preparation**  
   - Loaded `advertising.csv` dataset (from Kaggle).  
   - Key columns:  
     - `TV` → Advertising budget on TV  
     - `Radio` → Advertising budget on Radio  
     - `Newspaper` → Advertising budget on Newspaper  
     - `Sales` → Product sales (target variable)  

2. **Data Preprocessing**  
   - Checked for missing values and ensured data quality.  
   - Verified data distribution and correlation between features.  
   - Outliers found in `Newspaper` but ignored due to weak correlation with target.  

3. **Exploratory Data Analysis (EDA)**  
   - Sales strongly correlated with **TV and Radio ads**.  
   - Newspaper ads had little to no impact on sales.  
   - Key insights:  
     - **TV advertising** has the highest impact on sales.  
     - **Radio advertising** also contributes significantly.  
     - **Newspaper ads** have minimal influence on sales outcomes.  

4. **Modeling & Evaluation**  
   - Trained and evaluated multiple regression models:  
     **Linear Regression, Ridge, Lasso, ElasticNet, KNN, Decision Tree, Random Forest, XGBoost, Gradient Boosting**.  
   - Evaluation metrics: **R² Score (primary), MAE, MSE, RMSE, MAPE**.  

---

## 🛠️ Tools & Libraries  
- **Python, Jupyter Notebook**  
- **pandas, numpy** (data preprocessing)  
- **matplotlib, seaborn** (visualization)  
- **scikit-learn, XGBoost** (model building & evaluation)  

---

## 📈 Results  

| Model                     | R² Score | MSE   |
|---------------------------|----------|-------|
| Gradient Boosting Regressor | **0.9834** | **0.523** |
| Random Forest Regressor     | 0.9804   | 0.619 |
| XGBoost Regressor           | 0.9803   | 0.620 |
| Decision Tree Regressor     | 0.9414   | 2.427 |
| KNN Regressor               | 0.9106   | 2.821 |
| Linear Regression           | 0.8994   | 3.174 |
| Ridge Regression            | 0.8994   | 3.174 |
| ElasticNet Regression       | 0.8995   | 3.173 |
| Lasso Regression            | 0.8996   | 3.171 |

✅ **Best Model:** **Gradient Boosting Regressor** with **R² = 0.9834** and **lowest MSE = 0.523**.  

---

## 🎯 Outcome  
- Successfully built a robust **sales prediction model**.  
- **Gradient Boosting Regressor** achieved the highest accuracy (**98.3% R² Score**), outperforming Random Forest and XGBoost.  
- **TV and Radio ads** are the most influential factors driving sales, while **Newspaper ads** contribute minimally.  
- Demonstrated the importance of **ensemble methods** and **feature correlation analysis** in predictive modeling.  

---

👨‍💻 Developed as part of the **Data Science Internship at Oasis Infobyte**  
