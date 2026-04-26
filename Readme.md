# 🚀 Next Word Prediction using LSTM

## 📌 Overview

Built a deep learning-based Next Word Prediction system using LSTM networks trained on literary text. The application predicts the most probable next word given an input sequence and is deployed using Streamlit for real-time interaction.

---

## 🎯 Problem Statement

Language models are fundamental in NLP applications like autocomplete, chatbots, and text generation. This project focuses on building a word-level prediction system using sequence modeling.

---

## 🧠 Approach

* Cleaned and tokenized text data from *Hamlet*
* Generated n-gram sequences for training
* Applied padding for uniform input length
* Built and trained an LSTM-based neural network
* Used softmax activation for multi-class word prediction

---

## ⚙️ Tech Stack

* **Programming:** Python
* **Libraries:** TensorFlow, Keras, NumPy
* **Deployment:** Streamlit
* **Model Type:** LSTM (Sequence Model)

---

## 📊 Model Details

* Input: Sequence of words
* Output: Probability distribution over vocabulary
* Loss Function: Categorical Crossentropy
* Optimizer: Adam

---

## 🚀 Key Features

* Real-time next word prediction
* Handles variable-length input sequences
* Interactive UI using Streamlit
* End-to-end pipeline (training → deployment)

---

## 📂 Project Structure

```
├── app.py                  # Streamlit UI
├── Model_Training.ipynb    # Model building & training
├── next_word_predictor.h5  # Trained LSTM model
├── tokenizer.pkl           # Tokenizer object
├── hamlet.txt              # Training dataset
└── README.md
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## 📈 Results

* Successfully predicts context-aware next words
* Demonstrates sequence learning using LSTM
* Works in real-time with user input

---

## 🚧 Future Improvements

* Use larger datasets (e.g., Wikipedia, news corpus)
* Implement transformer-based models (e.g., GPT-style)
* Add top-k predictions instead of single output
* Deploy on cloud (AWS / Render / HuggingFace Spaces)

---

## 💡 What I Learned

* Sequence modeling using LSTM
* Tokenization and text preprocessing
* Handling variable-length sequences
* Deploying ML models with Streamlit

---

## 📬 Contact

(MOHAMMAD SHAHZAIB RAZA + [GitHub Link](https://github.com/Md-Shahzaib-Raza))