# 🧠 PhishVision – Email Phishing Detection using Machine Learning

PhishVision is an AI-powered email phishing detection model built using Python and trained on Kaggle phishing email datasets.  
The model analyzes email text and predicts whether it’s **Phishing** or **Legitimate**, helping users identify online scams effectively.

---

## 📊 Project Overview

- **Goal:** Detect phishing emails using NLP and ML.
- **Platform:** Google Colab
- **Dataset:** Kaggle – Phishing Email Detection Dataset
- **Model Used:** Logistic Regression
- **Accuracy Achieved:** 95.82%  
- **Language:** Python  
- **Libraries Used:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

---

## 📁 Files in This Repository

| File | Description |
|------|--------------|
| `PhishVision.ipynb` | Google Colab notebook with full code |
| `screenshots/` | Contains model accuracy, dataset samples, and output images |
| `README.md` | Project documentation (this file) |

---

## 🚀 How It Works

1. **Data Preprocessing:** Cleans and tokenizes email text.  
2. **Feature Extraction:** Converts text into numerical vectors using TF-IDF.  
3. **Model Training:** Trains ML classifier to detect phishing patterns.  
4. **Evaluation:** Tests model accuracy, precision, recall, and F1-score.  
5. **Prediction:** Takes email text input and predicts if it’s phishing.

---

## 📸 Screenshots

### 📂 Dataset Sample
![Dataset Screenshot](screenshots/data.png)

### 📈 Model Accuracy
![Accuracy Screenshot](screenshots/data-accuracy.png)

### ✅ Final Output
![Output Screenshot](screenshots/data-output.png)

---

## 🧩 Future Improvements
- Add Streamlit UI for live predictions  
- Integrate with email APIs (Gmail/Outlook)  
- Deploy on web for real-time phishing detection  


---

## 🏷️ Tags
`#AI` `#Cybersecurity` `#MachineLearning` `#PhishingDetection` `#Python` `#DataScience` `#NLP`
