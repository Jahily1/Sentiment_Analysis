# Sentiment Analysis: Transformers vs. Tree-Based Models

## 📌 Project Overview
This project benchmarks the performance gap between traditional machine learning methods and state-of-the-art deep learning architectures for sentiment analysis. Using English Twitter data from the CardiffNLP dataset, I compared the effectiveness of traditional tree-based models against a fine-tuned **XLM-T Transformer** model.

The goal was to determine if traditional models, which are computationally "cheaper," can still compete with modern Transformers in the nuance of social media language.

## 🚀 Key Findings
* **The Performance Gap:** The fine-tuned **XLM-T model** substantially outperformed both Random Forest and XGBoost, proving that transformer architectures are significantly better at capturing context and sarcasm in short-form text.
* **Model Comparison:** * **XLM-T (Transformer):** Achieved the highest macro-F1 score and accuracy by leveraging pre-trained multilingual knowledge.
    * **XGBoost & Random Forest:** While faster to train using TF-IDF vectorization, they struggled with the linguistic complexity and informal structure of tweets.
* **Optimization:** Successfully implemented model fine-tuning and text vectorization techniques to maximize the predictive power of each architecture.

## 🛠️ Tech Stack
* **Deep Learning:** Transformers (`Hugging Face`), PyTorch/TensorFlow
* **Machine Learning:** XGBoost, Random Forest (`Scikit-learn`)
* **NLP Techniques:** TF-IDF Vectorization, Tokenization, Sentiment Polarity
* **Language:** Python

## 📂 Methodology
1. **Data Acquisition:** Utilized the CardiffNLP Twitter dataset.
2. **Preprocessing:** Cleaned and prepared social media text for both traditional and deep learning pipelines.
3. **Training:** * Developed and tuned **Random Forest** and **XGBoost** models.
    * Fine-tuned a pre-trained **XLM-T** transformer model.
4. **Evaluation:** Measured performance using Macro-F1 score, Accuracy, Precision, and Recall.

---

## 📄 Full Project Report
For the detailed methodology, confusion matrices, and a deep dive into the statistical results, view the full report here:

👉 **[Download Project Report (PDF)](https://github.com/Jahily1/Sentiment_Analysis/blob/main/Project%20Report.pdf)**

---
*Note: This project was developed as part of the Sentiment Analysis course (BAM3034) at Lambton College.*
