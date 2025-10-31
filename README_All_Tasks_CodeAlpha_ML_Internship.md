
# CodeAlpha Machine Learning Internship – All Tasks

## 👩‍💻 Overview
This repository contains all four machine learning projects completed during the **CodeAlpha Machine Learning Internship**.  
Each task focuses on applying core ML principles — including data preprocessing, model building, evaluation, and visualization — across different problem domains.

---

## 🏦 **Task 1 – Credit Scoring Model**
### 🎯 Objective
To predict whether a customer is likely to default on a loan using historical financial and demographic data.

### 📊 Dataset Description
The dataset includes synthetic customer records with features such as income, age, loan amount, credit score, and default history.

| Feature | Description |
|----------|-------------|
| `age` | Age of the customer |
| `income` | Monthly or annual income |
| `loan_amount` | Total loan requested |
| `credit_score` | Calculated credit score |
| `loan_status` | Target variable (1 = Default, 0 = No Default) |

### ⚙️ Workflow
1. Data preprocessing and feature scaling using `StandardScaler`  
2. Model building using Logistic Regression, Decision Tree, and Random Forest  
3. Evaluation using Accuracy, ROC-AUC, and Classification Report  

### 📈 Results
Random Forest achieved the best accuracy (~88%) and ROC-AUC score (~0.91).  

### 🧰 Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib

---

## 🎤 **Task 2 – Emotion Recognition from Speech**
### 🎯 Objective
To identify emotional states from human speech using acoustic features such as pitch, energy, and MFCCs.

### 📊 Dataset Description
500 synthetic samples representing audio segments with extracted speech features.

| Feature | Description |
|----------|-------------|
| `pitch_mean`, `pitch_std` | Mean and variance of voice pitch |
| `energy_mean`, `energy_std` | Loudness variation in speech |
| `mfcc1`–`mfcc4` | Mel Frequency Cepstral Coefficients |
| `zero_crossing_rate` | Voice signal tone changes |
| `spectral_centroid` | Brightness of the speech signal |
| `emotion` | Target label (happy, sad, angry, fear, neutral, surprise) |

### ⚙️ Workflow
1. Feature scaling and preprocessing  
2. Model training using Random Forest and SVM classifiers  
3. Evaluation with confusion matrix and F1-score  

### 📈 Results
Accuracy achieved around 85–90%. Random Forest provided consistent classification performance.

### 🧰 Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

---

## ✍️ **Task 3 – Handwritten Digit Recognition**
### 🎯 Objective
To classify handwritten digits (0–9) using supervised learning algorithms.

### 📊 Dataset Description
A synthetic dataset of 500 samples simulating flattened 8×8 grayscale images (64 pixel values per image).

| Feature | Description |
|----------|-------------|
| `pixel_0`–`pixel_63` | Pixel intensity values (0–16) |
| `label` | Target digit (0–9) |

### ⚙️ Workflow
1. Feature scaling and reshaping of image data  
2. Model training using Support Vector Machine (SVM) and Random Forest  
3. Evaluation with accuracy and confusion matrix visualization  

### 📈 Results
Achieved over 90% accuracy on test data using the SVM model.

### 🧰 Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib

---

## 🩺 **Task 4 – Heart Disease Prediction**
### 🎯 Objective
To predict the likelihood of heart disease in patients based on clinical data and test results.

### 📊 Dataset Description
600 synthetic patient records with clinical and diagnostic features.

| Feature | Description |
|----------|-------------|
| `age`, `sex`, `cp` | Demographic and chest pain type data |
| `trestbps`, `chol` | Blood pressure and cholesterol levels |
| `thalach`, `exang`, `oldpeak` | Heart rate, exercise angina, and ECG results |
| `target` | Target variable (1 = Disease, 0 = No Disease) |

### ⚙️ Workflow
1. Data preprocessing and scaling  
2. Model training using Logistic Regression, Decision Tree, and Random Forest  
3. Evaluation using Accuracy, Precision, Recall, and ROC Curve  

### 📈 Results
Random Forest achieved ~86% accuracy and provided interpretable feature importances.

### 🧰 Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

---

## 🧩 **Conclusion**
Throughout the internship, the projects covered essential aspects of applied machine learning — data preprocessing, feature engineering, model selection, hyperparameter tuning, and evaluation.  
Each task demonstrated ML’s versatility across domains like **finance, audio analysis, computer vision, and healthcare**.

### 🏁 Final Deliverables
| Task | Files |
|------|--------|
| Task 1 | Task1(Sachik).ipynb, credit_scoring_data.csv, README_Task1_CreditScoring.md |
| Task 2 | Task2(Sachik).ipynb, emotion_recognition_data.csv, README_Task2_EmotionRecognition.md |
| Task 3 | Task3(Sachik).ipynb, handwritten_digit_data.csv, README_Task3_HandwrittenDigitRecognition.md |
| Task 4 | Task4(Sachik).ipynb, heart_disease_data.csv, README_Task4_HeartDiseasePrediction.md |

---

📚 **Submitted by:** *Sachi Kangutkar*  
📅 **Date:** November 2025  
🏢 **Internship Program:** CodeAlpha Machine Learning Internship
