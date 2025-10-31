# Task 4: Heart Disease Prediction Model
### CodeAlpha - Machine Learning Internship

## 📘 Project Overview
This project focuses on developing a **Heart Disease Prediction Model** that classifies whether a person is likely to have heart disease based on various medical attributes. It applies supervised learning techniques to assist in healthcare analytics and preventive diagnostics.

The model predicts the presence or absence of heart disease using clinical data such as age, cholesterol, blood pressure, and other cardiovascular indicators.

---

## 📂 Dataset Description
The dataset `heart_disease_data.csv` contains **600 samples** of synthetic health records resembling real-world data used for heart disease prediction.

| Column Name | Description |
|--------------|-------------|
| age | Age of the patient |
| sex | Gender (0 = female, 1 = male) |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol level (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| restecg | Resting electrocardiographic results (0–1) |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina (1 = yes, 0 = no) |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels (0–3) |
| thal | Thalassemia (0–2) |
| target | Target variable (1 = disease, 0 = no disease) |

---

## ⚙️ Technologies Used
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn (Logistic Regression, Random Forest, SVM)  
- Matplotlib, Seaborn (for visualization)

---

## 🚀 Steps Performed in the Notebook
1. **Import Libraries** – Load required packages.  
2. **Load Dataset** – Import `heart_disease_data.csv` into a pandas DataFrame.  
3. **Data Preprocessing** – Handle missing values, encode categorical variables, and scale numeric features.  
4. **Model Training** – Train models like Logistic Regression, Random Forest, and SVM.  
5. **Evaluation** – Use Accuracy, Precision, Recall, F1-score, and ROC-AUC metrics.  
6. **Visualization** – Plot correlation heatmaps and ROC curves.

---

## 📊 Results
The prediction model achieved strong classification accuracy, successfully identifying key features influencing heart disease likelihood.

---

## 💾 How to Run
1. Place `Task 4(sachik).ipynb` and `heart_disease_data.csv` in the same directory.  
2. Open in **Jupyter Notebook** or **Google Colab**.  
3. Run all cells to view the predictions and visualizations.

---

## 🧠 Learning Outcome
This project provided experience in **healthcare data analytics**, **classification modeling**, and interpreting medical datasets for predictive healthcare systems.

---

## ✍️ Author
**Sachi Kangutkar**  
CodeAlpha Machine Learning Intern (2025)
