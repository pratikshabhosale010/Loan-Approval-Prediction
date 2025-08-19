# Loan Approval Prediction

This project uses machine learning to predict whether a loan application should be approved or not. It aims to assist banks and financial institutions in making data-driven, risk-aware decisions by analyzing past applicant and loan data.

---

## 📌 Objective

To develop and compare multiple ML models (Logistic Regression, SVM, Decision Tree) that predict the approval status of loan applications based on applicant information like income, credit history, and business value.

---

## 🧠 Models Used

- Logistic Regression (Best accuracy: 79.03%)
- Support Vector Machine (SVM) (69.35%)
- Decision Tree (66.13%)

---

## 🛠️ Workflow

1. **Data Collection**: 1500 cases with 10 numerical + 8 categorical features
2. **Preprocessing**:
   - Handling missing values
   - Encoding categorical variables (e.g., one-hot encoding)
   - Feature scaling and selection
3. **Model Training**: Train/test split + cross-validation
4. **Evaluation**:
   - Accuracy
   - Precision
   - Confusion matrix
   - Cross-validation scores

---

## 📊 Results Summary
- Logistic Regression performed best, showing high accuracy and simplicity.
- SVM handled nonlinearities well but underperformed LR.
- Decision Tree was most interpretable, though with lower accuracy.

## ⚙️ Technologies
- Python (Jupyter Notebook)
- Libraries: pandas, sklearn, matplotlib, seaborn
- Algorithms: Logistic Regression, SVM, Decision Tree

