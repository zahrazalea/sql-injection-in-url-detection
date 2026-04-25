# 🔐 SQL Injection Detection in URLs using Machine Learning

A lightweight machine learning system to detect **SQL injection attacks** from URL inputs using NLP-based feature engineering and classification models. This project demonstrates an end-to-end pipeline from data preprocessing to model inference.

---

## 📌 Project Overview

SQL injection is one of the most common web security vulnerabilities. This project aims to:

- Classify URLs as **malicious (SQL injection)** or **benign**
- Apply **NLP techniques** to transform URL strings into machine-readable features
- Evaluate multiple machine learning models for optimal performance
- Provide a simple **runtime interface for testing predictions**

---

## 🧠 Methodology

### 1. Data Preprocessing
- Cleaned and standardized URL inputs
- Removed noise and handled special characters
- Applied regex-based pattern handling

### 2. Feature Engineering
- Transformed text into numerical representations using:
  - **TF-IDF Vectorizer**
  - **CountVectorizer**
- Generated **n-gram features** to capture SQL injection patterns

### 3. Model Development
- Trained and compared:
  - **Naive Bayes**
  - **Logistic Regression**
- Evaluated using:
  - Accuracy
  - Precision
  - Recall

### 4. Inference Interface (Runtime)
- Implemented a **Gradio-based interface** for local, runtime testing  
- Allows users to input URLs and receive real-time predictions during execution  
- Not deployed as a persistent web service (runs within notebook/session)

---

## ⚙️ Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, Scikit-learn, NumPy, Regex, Joblib  
- **Visualization:** Matplotlib, Wordcloud  
- **Interface (Runtime):** Gradio  
- **Tools:** Jupyter Notebook / VS Code  

---

## 📊 Results

- Successfully classified SQL injection patterns from URL inputs  
- Demonstrated effectiveness of **TF-IDF + classical ML models** for text-based security tasks  
- Logistic Regression and Naive Bayes showed strong performance on structured text data  
