# 🔐 SQL Injection Detection in URLs using Machine Learning

A lightweight machine learning system to detect **SQL injection attacks** from URL inputs using NLP-based feature engineering and classification models. This project demonstrates an end-to-end pipeline from data preprocessing to model deployment.

---

## 📌 Project Overview

SQL injection is one of the most common web security vulnerabilities. This project aims to:

- Classify URLs as **malicious (SQL injection)** or **benign**
- Apply **NLP techniques** to transform URL strings into machine-readable features
- Evaluate multiple machine learning models for optimal performance
- Deploy a simple interface for **real-time prediction**

---

## 🧠 Methodology

### 1. Data Preprocessing
- Cleaned and standardized URL inputs
- Removed noise and irrelevant characters
- Applied regex-based parsing for pattern extraction

### 2. Feature Engineering
- Converted text into numerical features using:
  - **TF-IDF Vectorizer**
  - **CountVectorizer**
- Generated **n-gram representations** to capture injection patterns

### 3. Model Development
- Trained and compared:
  - **Naive Bayes**
  - **Logistic Regression**
- Evaluated using:
  - Accuracy
  - Precision
  - Recall

### 4. Deployment
- Built a simple web interface using **Gradio**
- Enabled users to input URLs and receive real-time predictions

---

## ⚙️ Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, Scikit-learn, NumPy, Regex, Joblib  
- **Visualization:** Matplotlib, Wordcloud  
- **Deployment:** Gradio  
- **Tools:** Jupyter Notebook / VS Code  

---

## 📊 Results

- Successfully classified SQL injection patterns from URL inputs  
- Logistic Regression and Naive Bayes performed effectively for text-based classification  
- Demonstrated ability to generalize detection on unseen inputs  

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/zahrazalea/sql-injection-in-url-detection.git
cd sql-injection-in-url-detection
