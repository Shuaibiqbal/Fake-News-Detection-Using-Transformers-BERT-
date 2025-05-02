# Fake-News-Detection-Using-Transformers-BERT-
A simple implementation of a fake news detection system using a pre-trained BERT model from Hugging Face. The project uses the fetch_20newsgroups dataset to simulate binary classification between real and fake news, showcasing the power of transformer-based models for NLP tasks.

This project demonstrates how to use a pre-trained BERT model to classify news articles as real or fake. It uses the `fetch_20newsgroups` dataset from scikit-learn to simulate a fake news detection task using two categories: `sci.space` (real) and `talk.politics.misc` (fake).

---

## 🚀 Features

- Binary classification (Real vs Fake News)
- Utilizes Hugging Face's `transformers` library
- Uses BERT (bert-base-uncased)
- Clean, step-by-step PyTorch pipeline
- Simple dataset simulation using scikit-learn

---

## 📦 Installation

```bash
pip install transformers scikit-learn torch pandas
