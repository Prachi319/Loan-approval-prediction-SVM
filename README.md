# 🏦 Loan Approval Prediction using SVM

This project predicts whether a loan application should be approved or not using the **Support Vector Machine (SVM)** algorithm. The model is trained on historical loan data and takes into account various applicant details such as income, credit history, employment, and more.

---

## 📌 Problem Statement

Financial institutions receive thousands of loan applications. Manually checking each one is time-consuming. This project aims to automate that process using machine learning, specifically an SVM model, to predict loan approval outcomes.

---

## 📂 Dataset

The dataset typically includes the following features:

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area  
- **Target Variable:** Loan_Status (Y/N)

> The dataset can be found on platforms like [Kaggle](https://www.kaggle.com/)

---

## ⚙️ Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)
- Scikit-learn (SVM, preprocessing, train-test split)
- Google Colab

---

## 🧠 Model Used

- **Support Vector Machine (SVM)**  
  A powerful supervised learning model suitable for classification problems. In this case, it is used to classify loan applications as 'Approved' or 'Not Approved'.

---

## 🔄 Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
  
2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis
  
3. **Model Building**
   - Splitting data into train/test sets
   - Training the SVM model
 
4. **Model Evaluation**
   - Accuracy

---

## 📊 Results

The trained SVM model achieved good accuracy on unseen data, indicating that it can generalize well and be used for real-world applications (with further optimization and validation).

