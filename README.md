# Cantiever Labs tasks: Fraud Detection & Sentiment Analysis 🤖🚀

This repository contains two core Machine Learning projects focusing on diverse domains: **Financial Security (Fraud Detection)** and **Natural Language Processing (Movie Sentiment Analysis)**. These projects demonstrate data preprocessing, handling imbalanced datasets, and model optimization.

---

## 🛡️ Project 1: Indian Online Scam & Fraud Detection
An AI-driven system developed to identify fraudulent transactions within the Indian financial ecosystem.

### 📌 Key Features
* **Indian Context:** Analyzes transaction patterns across cities like Mumbai, Bangalore, and Surat.
* **Payment Methods:** Includes local payment gateways and card types like **RuPay**.
* **Overfitting Mitigation:** Implemented pruning (`max_depth`, `min_samples_leaf`) to ensure the model generalizes well to new data.

### 🛠️ Tech Stack & Methods
* **Models:** Random Forest (Optimized) vs. XGBoost.
* **Preprocessing:** `StandardScaler`, Label Encoding, and Median Imputation for missing values.
* **Evaluation:** Focused on **F1-Score** and **Confusion Matrix** to account for class imbalance (Fraud vs. Genuine).

---

## 🎬 Project 2: Movie Rating Sentiment Analysis
A Natural Language Processing (NLP) project that classifies user reviews into sentiments (Positive/Negative) to predict movie ratings.

### 📌 Key Features
* **Text Preprocessing:** Tokenization, Stop-word removal, and Lemmatization to clean raw review data.
* **Vectorization:** Implementation of **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert text into numerical features.
* **Analysis:** Classification of reviews to understand audience reception.

### 🛠️ Tech Stack & Methods
* **Models:** Multinomial Naive Bayes / Logistic Regression.
* **Libraries:** `NLTK`, `Scikit-Learn`, `Pandas`.
* **Metric:** Accuracy and Recall (to ensure negative reviews are not missed).

---

## 📊 Comparative Performance

| Project | Core Model | Key Metric | Result |
| :--- | :--- | :--- | :--- |
| **Fraud Detection** | Random Forest | F1-Score | 0.88 |
| **Sentiment Analysis** | Naive Bayes | Accuracy | 91% |

---

## 🚀 How to Run (Google Colab / Local)

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/ML-Portfolio.git](https://github.com/yourusername/ML-Portfolio.git)
