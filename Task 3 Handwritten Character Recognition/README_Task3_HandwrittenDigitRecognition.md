# Task 3: Handwritten Digit Recognition Model
### CodeAlpha - Machine Learning Internship

## 📘 Project Overview
This project involves developing a **Handwritten Digit Recognition Model** capable of identifying digits (0–9) from image data. It is a core supervised learning problem often solved using classification algorithms.  

The model uses machine learning techniques to recognize numerical digits based on pixel intensity values, demonstrating computer vision and pattern recognition skills.

---

## 📂 Dataset Description
The dataset `handwritten_digit_data.csv` is a synthetic dataset created for demonstration purposes. It mimics features similar to the **scikit-learn digits dataset**, containing pixel intensity values for 8×8 grayscale images.

| Column Name | Description |
|--------------|-------------|
| pixel_0 … pixel_63 | Flattened pixel values representing an 8×8 image (0–16 range) |
| label | Target variable (digit 0–9) |

The dataset contains **500 samples** with 64 features per image and corresponding digit labels.

---

## ⚙️ Technologies Used
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn (for model training and evaluation)  
- Matplotlib, Seaborn (for visualization)

---

## 🚀 Steps Performed in the Notebook
1. **Data Loading** – Load the `handwritten_digit_data.csv` dataset.  
2. **Data Preprocessing** – Normalize pixel values for model readiness.  
3. **Train-Test Split** – Divide data into training and testing subsets.  
4. **Model Building** – Train classification models such as Logistic Regression, SVM, Random Forest, or CNN.  
5. **Model Evaluation** – Evaluate accuracy, confusion matrix, and classification report.  
6. **Visualization** – Display sample digits with predicted and actual labels.

---

## 📊 Results
The model successfully classifies handwritten digits with high accuracy, demonstrating the effectiveness of supervised classification in image recognition tasks.

---

## 💾 How to Run
1. Place `Task3(Sachik).ipynb` and `handwritten_digit_data.csv` in the same folder.  
2. Open in Jupyter Notebook or Google Colab.  
3. Run all cells sequentially to reproduce results.

---

## 🧠 Learning Outcome
This task strengthened understanding of **computer vision**, **image preprocessing**, and **classification algorithms** used in OCR and digit recognition systems.

---

## ✍️ Author
**Sachi Kangutkar**  
CodeAlpha Machine Learning Intern (2025)
