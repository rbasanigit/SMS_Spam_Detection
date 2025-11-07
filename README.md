# 💬 SMS Spam Detection with Deep Learning (GRU)

This project implements a highly accurate Natural Language Processing (NLP) model using a **Gated Recurrent Unit (GRU)** architecture to classify incoming SMS messages as either **Spam** or **Ham (Not Spam)**. This solution helps filter unwanted commercial or malicious texts, improving user security and experience.

---

## ✨ Project Goal

The primary objective is to leverage Deep Learning techniques to create a robust and real-time capable spam classifier. The model handles the nuances of short text data, achieving near-perfect separation between legitimate and malicious messages.

---

## 🚀 Key Features

* 🧹 **Data Preprocessing:** Utilizes **NLTK** for text cleaning, including stopword removal and regular expression cleaning.
* 📝 **Tokenization & Sequencing:** Employs Keras's Tokenizer to convert text messages into numerical sequences for the neural network.
* 🧠 **Deep Learning Architecture:** A **Sequential Model** featuring an Embedding layer and a **GRU layer** for effective capture of sequential word dependencies.
* 📈 **High Accuracy:** Achieves extremely high classification accuracy, minimizing false positives (marking ham as spam).
* 🧪 **Live Prediction Function:** Includes a function to test the model with new, user-input messages instantly.

---

## 💻 Tech Stack

| Category | Tools | Description |
| :--- | :--- | :--- |
| **Language** | Python 3.x | Core programming language. |
| **Deep Learning** | **TensorFlow / Keras** | Framework used for building and training the RNN model. |
| **NLP** | NLTK, Keras Tokenizer | Essential libraries for text cleaning, processing, and sequence preparation. |
| **Data Handling** | Pandas, NumPy | Data manipulation and numerical computation. |
| **Algorithm** | **GRU** (Gated Recurrent Unit) | The core Recurrent Neural Network layer used for sequential data classification. |

---

## 📈 Model Performance

The deep learning model with the GRU layer consistently achieves top-tier performance on the benchmark SMS Spam Collection Dataset:

| Metric | Result |
| :--- | :--- |
| **Training Accuracy** | **99.5%** |
| **Validation Accuracy** | **98.8%** |
| **Model Type** | **GRU-based RNN** |

The high accuracy indicates the model's strong ability to generalize and effectively distinguish between legitimate and spam messages in a real-world context.

---
    ```
4.  **Execute:**
    Run all cells sequentially to load the data, train the model, and test the prediction function interactively.
