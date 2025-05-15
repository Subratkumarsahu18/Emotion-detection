# 🧠 Emotion Detection from Text

This project detects human emotions such as **joy**, **sadness**, **anger**, **fear**, **love**, and **surprise** from raw text input using machine learning. It uses a real-world dataset from Hugging Face and is trained with a Naive Bayes classifier and TF-IDF vectorization.

---

## 📂 Dataset

- **Source:** [DAIR-AI Emotion Dataset](https://huggingface.co/datasets/dair-ai/emotion)
- **Size:** ~16,000 labeled text samples
- **Classes:** `joy`, `sadness`, `anger`, `fear`, `love`, `surprise`

---

## ⚙️ Technologies Used

- Python 3.x
- pandas
- scikit-learn
- neattext
- joblib

---

## 🚀 Features

- Text cleaning using `neattext`
- Text vectorization using **TF-IDF**
- Emotion classification using **Multinomial Naive Bayes**
- Accuracy of **~78%** on test data
- Real-time user input prediction support

---

## 📈 Model Performance

- **Accuracy:** ~78%
- **High Recall:** `joy`, `sadness`
- **Needs Improvement:** `love`, `surprise`
