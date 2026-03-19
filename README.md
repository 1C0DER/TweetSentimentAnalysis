# 🧠 Sentiment Analysis (Tweet Classification)

## 📌 Overview
This project builds and evaluates machine learning models to classify tweets into:
- Positive  
- Negative  
- Neutral  

It follows a full NLP pipeline: preprocessing → feature extraction → model training → evaluation.

---

## 🛠️ Tech Stack
- Language: Python  
- Environment: Jupyter Notebook / Colab  
- Libraries:
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib / seaborn  

---

## Pipeline

### 🔹 Data Processing
- Load dataset using pandas  
- Handle missing values  
- Check class distribution  

---

### 🔹 Text Preprocessing
- Lowercase text  
- Remove punctuation & special characters  
- Remove stopwords  
- Tokenization  

---

### 🔹 Feature Extraction
- TF-IDF Vectorization  
- Converts text into numerical features  

---

## Models Used

### 🔹 Naive Bayes
- Model: MultinomialNB  
- Fast baseline for text classification  

### 🔹 Logistic Regression
- Model: LogisticRegression  
- Handles high-dimensional TF-IDF data well  

### 🔹 Other Models
- Support Vector Machine (SVM)  
- Decision Tree / Random Forest  

---

## 📊 Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-score  

Models are compared to determine best performance.

---

## 🚀 Running the Project

```bash
git clone https://github.com/1C0DER/AAI-Repo
```

1. Open the notebook:
```
Joan_AAI_Coursework.ipynb
```

2. Run all cells in order

---

## 📌 Notes
- Runs entirely in notebook  
- No backend required  
- Can be extended with deep learning (LSTM, BERT)  
