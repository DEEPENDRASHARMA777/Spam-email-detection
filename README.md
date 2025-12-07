<!-- PROJECT LOGO -->
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2986/2986666.png" alt="Logo" width="120">
</p>

<h1 align="center">📧 Spam Email Detection using Machine Learning</h1>

<p align="center">
  Identify and filter unwanted emails using NLP + ML models  
  <br />
  <strong>Clean • Accurate • Fully Scalable</strong>
</p>

---

## ✨ Overview  
Spam emails pose serious threats such as phishing, fraud, scams, and malware. This project builds a **super-efficient machine learning solution** that classifies emails into **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** and **supervised learning algorithms**.

This repository includes:  
✔️ Data preprocessing pipeline  
✔️ Feature extraction using TF-IDF  
✔️ ML model training & tuning  
✔️ Evaluation metrics  
✔️ Final deployable model  

---

## 🚀 Key Features  
- 🔍 Clean & preprocess raw email text  
- 🧠 Train multiple ML algorithms  
- 🆚 Compare accuracy of different models  
- ⭐ Highly accurate final classification model  
- 🧰 Easy-to-understand modular code structure  
- 📈 Visualized performance metrics  

---

## 📂 Dataset Description  
The dataset contains thousands of emails labeled as:

| Label | Meaning |
|------|---------|
| **spam** | Unwanted or malicious emails |
| **ham** | Genuine, safe emails |

Popular datasets supported:  
- SMS Spam Collection Dataset  
- Enron Email Dataset  
- Custom corporate/company email datasets  

---

## 🛠️ Technologies & Tools  

### **🔧 Languages & Libraries**
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- NLTK (Natural Language Toolkit)  
- Regex (Text Cleaning)

### **🤖 Machine Learning Models**
- Multinomial Naive Bayes  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  

### **🧪 Evaluation Metrics**
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-Score  

---

## 🧠 Project Workflow  
```mermaid
flowchart TD
    A[Load Dataset] --> B[Clean & Preprocess Text]
    B --> C[Convert Text to Numerical Features using TF-IDF]
    C --> D[Train ML Models]
    D --> E[Compare Performance]
    E --> F[Select Best Model]
