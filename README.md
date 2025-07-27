# 🔁 Churn-Prediction-Model

## 📌 Customer Churn Detection using Machine Learning & Deep Learning

This project aims to predict whether a customer will churn (leave a service) based on various behavioral and demographic features. It helps businesses take proactive steps to retain valuable customers using both traditional classification models and deep learning.

---

## 📁 Dataset Features

- `Customer_ID`  
- `Gender`  
- `SeniorCitizen`  
- `Partner` (Yes/No)  
- `Dependents`  
- `Tenure` (in months)  
- `PhoneService`  
- `MultipleLines`  
- `InternetService` (DSL/Fiber/None)  
- `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`  
- `TechSupport`, `StreamingTV`, `StreamingMovies`  
- `Contract` (Month-to-month, One year, Two year)  
- `PaperlessBilling`  
- `PaymentMethod`  
- `MonthlyCharges`  
- `TotalCharges`  
- **`Churn`** (Target Variable: Yes/No)

---

## 🤖 Algorithms Used

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier    
- Support Vector Machine (SVM)  
- ✅ **Convolutional Neural Network (CNN)** *(Best Model)*

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC-AUC Score  

---

## 🏁 Final Result

The **Convolutional Neural Network (CNN)** gave the best performance with:

- **Accuracy**: 0.74  
- **Precision**: 0.74 (class 0), 0.00 (class 1)  
- **Recall**: 1.00 (class 0), 0.00 (class 1)  
- **F1-Score**: 0.85 (class 0), 0.00 (class 1)  
- **Weighted Avg F1-Score**: 0.63  

> ⚠️ *The CNN performed well on the majority class (non-churners), but struggled with minority class (churners) due to class imbalance.*

---

## 🔧 Tools Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  
- Seaborn  

---

## 📌 Author

**Aniket Appasaheb Vadak**  
📧 Email: aniketvadak672005@gmail.com  
💻 GitHub: [AniketVadak](https://github.com/AniketVadak)  
🔗 LinkedIn: [Aniket Vadak](https://www.linkedin.com/in/aniket-vadak-00a042268)
