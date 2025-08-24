# 📧 Email Spam Detection with Machine Learning

## 📌 Objective  
To build a predictive model that classifies emails/SMS messages as **spam** or **ham (legitimate)** using machine learning and natural language processing (NLP).  
The goal is to reduce unwanted, fraudulent, or phishing emails while ensuring legitimate messages are not filtered out.  

---

## 🔎 Steps Performed  
1. **Dataset Preparation**  
   - Used `spam.csv` dataset from Kaggle containing **5,574 messages** labeled as *spam* or *ham*.  

2. **Data Preprocessing**  
   - Cleaned and structured the dataset.  
   - Handled duplicates and irrelevant entries.  

3. **Text Preprocessing (NLP)**  
   - Tokenization, stop-word removal, stemming/lemmatization.  
   - Feature extraction using **TF-IDF vectorization** to convert text into numerical features.  

4. **Modeling & Evaluation**  
   - Trained and compared multiple ML models: **Naive Bayes, Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, Bagging, AdaBoost, KNN, SVM, XGBoost**.  
   - Evaluated using **Precision, Recall, F1-score, Training Accuracy, and Test Accuracy**.  

---

## 🛠️ Tools & Libraries  
- **Python, Jupyter Notebook**  
- **pandas, numpy** (data handling)  
- **scikit-learn, XGBoost** (modeling & evaluation)  
- **nltk** (text preprocessing)  
- **matplotlib, seaborn** (visualization)  

---

## 📈 Results  

| Model                     | Precision | Recall  | F1 Score | Train Accuracy | Test Accuracy |
|----------------------------|-----------|---------|----------|----------------|---------------|
| **XGBClassifier**          | 0.9541    | 0.8595  | 0.9043   | 0.9879         | **0.9787**    |
| **SVC**                    | 0.9541    | 0.8595  | 0.9043   | 0.9864         | **0.9787**    |
| RandomForestClassifier     | 0.9800    | 0.8099  | 0.8869   | 0.9998         | 0.9758        |
| BaggingClassifier          | 0.8710    | 0.8926  | 0.8816   | 0.9998         | 0.9719        |
| MultinomialNB              | 0.9889    | 0.7355  | 0.8436   | 0.9714         | 0.9681        |
| LogisticRegression         | 0.9417    | 0.8017  | 0.8661   | 0.9666         | 0.9710        |
| GradientBoostingClassifier | 0.9462    | 0.7273  | 0.8224   | 0.9722         | 0.9632        |
| KNeighborsClassifier       | 1.0000    | 0.3141  | 0.4780   | 0.9221         | 0.9197        |
| DecisionTreeClassifier     | 0.7850    | 0.6942  | 0.7368   | 0.9579         | 0.9419        |
| AdaBoostClassifier         | 0.7755    | 0.6281  | 0.6941   | 0.9351         | 0.9351        |

✅ **Best Model:** **XGBoost Classifier**, achieving **97.9% Test Accuracy** with strong **Precision (95.4%)** and **F1-score (90.4%)**.  
⚡ **SVM** performed equally well (97.9% accuracy), making both viable options depending on computational constraints.  

---

## 🎯 Outcome  
- Successfully built a spam detection system using **ML + NLP techniques**.  
- **XGBoost Classifier** emerged as the most reliable model with the best balance of precision, recall, and accuracy.  
- Extracted key insights on how different models perform under **imbalanced spam vs ham datasets**.  
- The system can be integrated into **email filtering pipelines** to improve inbox security.  

---

👨‍💻 Developed as part of the **Data Science Internship at Oasis Infobyte**  
