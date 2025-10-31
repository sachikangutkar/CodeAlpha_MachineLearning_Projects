# Task 1: Credit Scoring Model
### CodeAlpha - Machine Learning Internship

## 📘 Project Overview
This project focuses on building a **Credit Scoring Model** that predicts whether a loan applicant is likely to default based on their financial and demographic characteristics. It is part of the CodeAlpha Machine Learning Internship tasks.

The objective is to use historical data about customers (age, income, credit score, loan amount, and employment history) to train a classification model that can assess credit risk effectively.

---

## 📂 Dataset Description
The dataset used in this project is `credit_scoring_data.csv`, which contains synthetic data generated for demonstration purposes. It includes the following features:

| Column Name | Description |
|--------------|-------------|
| age | Age of the applicant (in years) |
| income | Annual income of the applicant (in USD) |
| loan_amount | Requested loan amount (in USD) |
| credit_score | Applicant's credit score (300–850) |
| years_employed | Total years of employment |
| default | Target variable (1 = default, 0 = no default) |

This dataset consists of **500 records** and is balanced to represent realistic credit approval patterns.

---

## ⚙️ Technologies Used
- Python 3.x  
- Pandas, NumPy (for data handling)  
- Scikit-learn (for model building and evaluation)  
- Matplotlib / Seaborn (for visualization)  

---

## 🚀 Steps Performed in the Notebook
1. **Import Libraries** – Load required packages for data manipulation, visualization, and machine learning.  
2. **Load Dataset** – Import `credit_scoring_data.csv` into a pandas DataFrame.  
3. **Data Exploration** – Analyze missing values, correlations, and distribution of target labels.  
4. **Data Preprocessing** – Apply scaling using `StandardScaler` to normalize continuous features.  
5. **Model Building** – Train multiple classification models such as Logistic Regression, Decision Tree, and Random Forest.  
6. **Model Evaluation** – Compare models using Accuracy, Precision, Recall, F1-score, and ROC-AUC metrics.  
7. **Conclusion** – Select the best-performing model for credit risk prediction.

---

## 📊 Results
The trained models achieved reliable classification accuracy with strong AUC performance, demonstrating their effectiveness for credit scoring tasks. Random Forest generally performed best due to its robustness against feature variability.

---

## 💾 How to Run
1. Open the `Task1(sachik).ipynb` file in Jupyter Notebook.  
2. Place the `credit_scoring_data.csv` file in the same directory.  
3. Run all cells sequentially to reproduce the results.

---

## 🧠 Learning Outcome
Through this task, I learned the end-to-end workflow of a supervised learning project — from dataset preparation to model deployment. It also strengthened my understanding of evaluation metrics crucial for financial risk prediction systems.

---

## ✍️ Author
**Sachi Kangutkar**  
CodeAlpha Machine Learning Intern (2025)
