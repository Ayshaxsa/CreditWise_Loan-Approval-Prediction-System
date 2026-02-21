# Credit Loan Approval Prediction System

## 📌 Project Overview
This project predicts whether a loan application will be approved using Machine Learning. The goal is to compare multiple classification models and select the most suitable one based on different metrics like precision, recall, and F1-score.

---

## 🧠 Models Used
- **Naive Bayes**  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression**  

---

## 📊 Model Performance

### 🔹 Naive Bayes
- Accuracy: 0.89  
- **Precision: 0.90** ✅ (highest)  
- Recall: 0.67  
- F1 Score: 0.77  
- Confusion Matrix:  [[119 26] [ 28 27]]


### 🔹 Logistic Regression
- Accuracy: 0.895  
- Precision: 0.84  
- Recall: 0.76  
- **F1 Score: 0.80** ✅ (best overall)  
- Confusion Matrix:  [[137 8] [ 13 42]]


---

## 🏆 Insights
- **Naive Bayes** is best for **precision**, making it ideal if minimizing false positives (approving risky loans) is your top priority.  
- **Logistic Regression** has the **best balance** between precision and recall, achieving the highest F1-score.  
- **KNN** performed less effectively on this dataset.

---

## 🛠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Joblib  
