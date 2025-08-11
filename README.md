# 🎬 Movie Hit or Flop Prediction using Machine Learning  

> **Predict the success of a movie before its release using ML models**  

This project leverages **machine learning** to predict whether a movie will be a commercial **🎯 Hit** or a **💤 Flop** before its release.  
It aims to support **producers, investors, and marketing teams** in making informed decisions and reducing financial risks.  

---

## 📌 Objectives  
- 📊 **Collect & preprocess** movie data from IMDb, TMDb, and Box Office Mojo.  
- 🤖 **Train classification models** – Gradient Boosting, Support Vector Machine (SVM), and Random Forest.  
- 🔍 Identify **key factors** influencing a movie’s performance.  
- 📈 Evaluate models using **Accuracy, Precision, Recall, and F1-Score**.

---

## 🔄 Methodology  

```mermaid
graph TD;
    A[Data Collection] --> B[Data Preprocessing];
    B --> C[Train-Test Split 80-20];
    C --> D[Model Training];
    D --> E[Model Evaluation];
    E --> F[Model Comparison];
