# 🌸 Iris Flower Classification

## 📌 Objective  
To build and evaluate machine learning models that classify Iris flowers into three species—**Setosa, Versicolor, and Virginica**—based on four morphological features: sepal length, sepal width, petal length, and petal width.  

---

## 🔎 Steps Performed  
- Loaded and explored the **Iris dataset** (150 records, 3 species, 4 features).  
- Conducted **exploratory data analysis (EDA)** using visualizations to identify feature importance (petal length and width were most discriminative).  
- Preprocessed data by dropping irrelevant columns, encoding the target, and splitting into training/testing sets.  
- Trained and evaluated multiple machine learning models: **Logistic Regression, KNN, SVM, Decision Tree, Naive Bayes, and Random Forest**.  

---

## 🛠️ Tools & Libraries  
- **Python, Jupyter Notebook**  
- **pandas, numpy** (data handling)  
- **matplotlib, seaborn** (visualization)  
- **scikit-learn** (modeling & evaluation)  

---

## 📈 Results  

| Model                     | Precision | Recall | F1-score | Accuracy |
|---------------------------|-----------|--------|----------|----------|
| Logistic Regression       | 1.0000    | 1.0000 | 1.0000   | 1.0000   |
| K-Nearest Neighbors       | 1.0000    | 1.0000 | 1.0000   | 1.0000   |
| Support Vector Machine    | 1.0000    | 1.0000 | 1.0000   | 1.0000   |
| Decision Tree             | 1.0000    | 1.0000 | 1.0000   | 1.0000   |
| Gaussian Naive Bayes      | 0.9766    | 0.9737 | 0.9739   | 0.9737   |
| Random Forest             | 0.9766    | 0.9737 | 0.9739   | 0.9737   |

---

## 🎯 Outcome  
- Achieved **100% accuracy** with Logistic Regression, KNN, SVM, and Decision Tree.  
- Naive Bayes and Random Forest also performed strongly (**97.3% accuracy**).  
- Confirmed that **petal length and width are the most significant features** for classification.  
- Demonstrated the effectiveness of classical ML models in solving a well-structured multiclass classification problem.  

---
👨‍💻 Developed as part of the **Data Science Internship at Oasis Infobyte**  
