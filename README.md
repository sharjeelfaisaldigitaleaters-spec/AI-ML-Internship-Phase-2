# 🚀 AI/ML Engineering Internship Projects

This repository contains a collection of projects completed during my **AI/ML Engineering Internship at DevelopersHub Corporation**. The projects cover various domains of Machine Learning, Deep Learning, Natural Language Processing (NLP), Large Language Models (LLMs), Prompt Engineering, and Production-Ready ML Pipelines.

The goal of these projects was to gain hands-on experience in building, training, evaluating, and deploying modern AI/ML solutions using industry-standard tools and frameworks.

---

# 📚 Projects Included

## 1️⃣ News Topic Classifier Using BERT

### Overview

A Natural Language Processing project that fine-tunes **BERT (bert-base-uncased)** on the **AG News Dataset** to automatically classify news headlines into four categories:

* 🌍 World
* ⚽ Sports
* 💼 Business
* 🔬 Sci/Tech

### Technologies

* Python
* PyTorch
* Hugging Face Transformers
* Scikit-Learn
* Gradio
* Matplotlib
* Seaborn

### Results

| Metric            | Value  |
| ----------------- | ------ |
| Accuracy          | 91.65% |
| Weighted F1 Score | 0.9165 |

### Key Features

✔ Fine-tuned BERT model

✔ News headline classification

✔ Interactive Gradio deployment

✔ Confusion matrix and loss visualization

✔ Model export for production use

---

## 2️⃣ End-to-End ML Pipeline for Customer Churn Prediction

### Overview

A production-ready machine learning pipeline built using **Scikit-Learn** to predict customer churn using the IBM Telco Customer Churn Dataset.

The project demonstrates the complete machine learning workflow from data preprocessing to model deployment.

### Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* Joblib
* Matplotlib
* Seaborn

### Models Implemented

* Logistic Regression
* Random Forest Classifier

### Results

| Model               | Accuracy | F1 Score | ROC-AUC |
| ------------------- | -------- | -------- | ------- |
| Logistic Regression | 80.55%   | 0.6040   | 0.8420  |
| Random Forest       | 80.06%   | 0.5800   | 0.8417  |

🏆 Best Model: Logistic Regression

### Key Features

✔ Automated preprocessing pipeline

✔ One-Hot Encoding & Feature Scaling

✔ Hyperparameter tuning using GridSearchCV

✔ ROC Curve analysis

✔ Feature importance visualization

✔ Exportable production pipelines using Joblib

---

## 3️⃣ Auto Tagging Support Tickets Using LLM

### Overview

An NLP project that compares **Prompt Engineering** and **Model Fine-Tuning** approaches for automatically categorizing customer support tickets.

Three approaches were implemented:

* Zero-Shot Classification (LLaMA 3 via Groq)
* Few-Shot Classification (LLaMA 3 via Groq)
* Fine-Tuned DistilBERT

### Ticket Categories

* Billing and Payments
* Customer Service
* IT Support
* Product Support
* Technical Support

### Technologies

* Python
* Groq API
* LLaMA 3.1
* DistilBERT
* Hugging Face Transformers
* PyTorch
* Scikit-Learn

### Results

| Approach              | Accuracy | F1 Score |
| --------------------- | -------- | -------- |
| Zero-Shot LLaMA 3     | 36.0%    | 0.3225   |
| Few-Shot LLaMA 3      | 52.0%    | 0.4768   |
| Fine-Tuned DistilBERT | 70.0%    | 0.6333   |

🏆 Best Approach: Fine-Tuned DistilBERT

### Key Features

✔ Prompt Engineering

✔ Zero-Shot Learning

✔ Few-Shot Learning

✔ DistilBERT Fine-Tuning

✔ Top-3 Tag Prediction

✔ Comparative Performance Analysis

---

# 🛠️ Skills Demonstrated

### Machine Learning

* Supervised Learning
* Classification
* Feature Engineering
* Model Evaluation
* Hyperparameter Optimization

### Deep Learning

* BERT Fine-Tuning
* DistilBERT Fine-Tuning
* Transfer Learning
* Transformer Architectures

### Natural Language Processing

* Text Classification
* Tokenization
* Prompt Engineering
* LLM Applications

### MLOps & Production

* Scikit-Learn Pipelines
* Model Serialization
* Reusable ML Workflows
* Interactive Model Deployment

---

# 📊 Project Summary

| Project                     | Domain           | Model               | Best Accuracy |
| --------------------------- | ---------------- | ------------------- | ------------- |
| News Topic Classifier       | NLP              | BERT                | 91.65%        |
| Customer Churn Prediction   | Machine Learning | Logistic Regression | 80.55%        |
| Support Ticket Auto Tagging | NLP + LLM        | DistilBERT          | 70.00%        |

---

# 📂 Repository Structure

```text
AI-ML-Internship-Projects/
│
├── News-Topic-Classifier-BERT/
│   ├── notebook.ipynb
│   ├── model/
│   └── README.md
│
├── Customer-Churn-ML-Pipeline/
│   ├── notebook.ipynb
│   ├── pipelines/
│   └── README.md
│
├── Auto-Tagging-Support-Tickets/
│   ├── notebook.ipynb
│   ├── distilbert-model/
│   └── README.md
│
└── README.md
```

---

# 🎯 Internship Learning Outcomes

Through these projects, I gained practical experience in:

* Building end-to-end machine learning systems
* Fine-tuning transformer-based NLP models
* Applying Large Language Models (LLMs) to real-world tasks
* Designing reusable production-ready ML pipelines
* Evaluating and comparing multiple AI approaches
* Deploying machine learning solutions for interactive use

---

# 👨‍💻 Author

**Muhammad Sharjeel Faisal**

Computer Science Undergraduate | AI/ML Enthusiast | Full-Stack Developer

### Connect With Me

* LinkedIn: [www.linkedin.com/in/muhammad-sharjeel-faisal](http://www.linkedin.com/in/muhammad-sharjeel-faisal)
* GitHub: https://github.com/Sharjeel-faisal

---

⭐ If you found these projects useful, consider giving the repository a star.
