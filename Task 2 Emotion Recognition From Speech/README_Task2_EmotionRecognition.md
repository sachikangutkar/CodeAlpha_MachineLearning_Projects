
# Task 2 – Emotion Recognition from Speech
### CodeAlpha - Machine Learning Internship

## 🧠 Objective
The aim of this project is to recognize **human emotions** from **speech signals** using machine learning. 
By analyzing acoustic properties such as pitch, energy, and Mel Frequency Cepstral Coefficients (MFCCs), 
the model identifies emotions like *happy*, *sad*, *angry*, *fear*, *neutral*, and *surprise*.

---

## 📊 Dataset Description
The dataset (`emotion_recognition_data.csv`) contains **500 synthetic samples**, each representing an audio segment 
with extracted acoustic features commonly used in emotion recognition systems.

### Features:
| Feature | Description |
|----------|-------------|
| `pitch_mean`, `pitch_std` | Mean and variation in speech pitch |
| `energy_mean`, `energy_std` | Loudness of the voice and its variation |
| `mfcc1`–`mfcc4` | Mel Frequency Cepstral Coefficients representing spectral envelope |
| `zero_crossing_rate` | Frequency of signal sign changes (voice tone) |
| `spectral_centroid` | Measure of signal brightness |
| `emotion` | Target label (happy, sad, angry, fear, neutral, surprise) |

---

## ⚙️ Workflow
1. **Data Loading** – Import dataset using Pandas.  
2. **Data Preprocessing** – Handle missing values, scale features using `StandardScaler`.  
3. **Model Selection** – Train classifiers like Random Forest, SVM, and Gradient Boosting.  
4. **Model Evaluation** – Evaluate performance using accuracy, precision, recall, and F1-score metrics.  
5. **Visualization** – Plot confusion matrix and feature importance for interpretability.

---

## 📈 Results
- Achieved approximately **85–90% accuracy** on test data.  
- Random Forest performed best with balanced results across all emotions.  
- Model generalizes well to unseen samples due to feature diversity.

---

## 🧰 Tools & Libraries
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**

---

## 💡 Conclusion
This project demonstrates how **machine learning can recognize emotional tone** from voice signals using 
speech-derived features. It forms the foundation for applications in **virtual assistants, call centers, 
and emotion-aware AI systems**.

---

### 📂 Files
- `Task2(Sachik).ipynb` – Jupyter Notebook code  
- `emotion_recognition_data.csv` – Dataset file  
- `README_Task2_EmotionRecognition.md` – Documentation file  
