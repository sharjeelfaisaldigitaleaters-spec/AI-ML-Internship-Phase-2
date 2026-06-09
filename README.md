# 📰 News Topic Classifier Using BERT

A deep learning NLP project that fine-tunes **BERT (bert-base-uncased)** on the **AG News Dataset** to automatically classify news headlines into four categories:

* 🌍 World
* ⚽ Sports
* 💼 Business
* 🔬 Sci/Tech

The model is trained using the Hugging Face Transformers ecosystem and achieves over **91% classification accuracy**.

---

## 🚀 Project Overview

News articles are generated at an enormous scale every day. Automatically categorizing news content helps improve:

* News recommendation systems
* Content organization
* Search and retrieval
* Personalized news feeds
* Media monitoring platforms

This project demonstrates how transformer-based language models can be fine-tuned for high-performance text classification.

---

## 📊 Dataset

**Dataset:** AG News Dataset

* Training Samples: 120,000
* Test Samples: 7,600
* Classes: 4

For faster experimentation:

* Training Subset: 8,000 samples
* Test Subset: 2,000 samples

### Categories

| Label | Category |
| ----- | -------- |
| 0     | World    |
| 1     | Sports   |
| 2     | Business |
| 3     | Sci/Tech |

---

## 🛠 Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* Scikit-Learn
* Matplotlib
* Seaborn
* Gradio

---

## ⚙️ Model Architecture

Base Model:

```text
bert-base-uncased
```

Configuration:

* Maximum Sequence Length: 128
* Epochs: 3
* Learning Rate: 2e-5
* Batch Size: 16
* Weight Decay: 0.01

---

## 📈 Results

### Overall Performance

| Metric            | Score  |
| ----------------- | ------ |
| Accuracy          | 91.65% |
| Weighted F1 Score | 0.9165 |
| Evaluation Loss   | 0.2967 |

### Classification Report

| Class    | Precision | Recall | F1 Score |
| -------- | --------- | ------ | -------- |
| World    | 0.94      | 0.90   | 0.92     |
| Sports   | 0.97      | 0.98   | 0.98     |
| Business | 0.92      | 0.86   | 0.89     |
| Sci/Tech | 0.85      | 0.93   | 0.89     |

---

## 📊 Visualizations

The project includes:

* Class Distribution Analysis
* Confusion Matrix
* Training Loss Curve
* Evaluation Loss Tracking

---

## 🌐 Gradio Deployment

An interactive Gradio application was built to test predictions in real-time.

Example Headlines:

* NASA launches new telescope to study distant galaxies
* Stock market hits record high amid strong earnings
* Brazil wins the World Cup in a thrilling final

The model returns category probabilities for all four classes.

---

## 💾 Model Export

The trained model and tokenizer are saved locally:

```bash
./bert-ag-news-final
```

Files include:

```text
config.json
model.safetensors
tokenizer.json
tokenizer_config.json
special_tokens_map.json
```

---

## 📂 Project Structure

```text
├── notebook.ipynb
├── bert-ag-news-final/
├── class_distribution.png
├── confusion_matrix.png
├── loss_curve.png
├── requirements.txt
└── README.md
```

---

## 🎯 Key Learnings

* Fine-tuning transformer models for NLP classification
* Tokenization and preprocessing with Hugging Face
* Model evaluation using Accuracy and F1 Score
* Building inference pipelines
* Deploying NLP models with Gradio

---

## 👨‍💻 Author

Muhammad Sharjeel Faisal

AI/ML Engineering Internship Project
