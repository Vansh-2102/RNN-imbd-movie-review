# RNN-imbd-movie-review

# 🎬 IMDB Movie Review Sentiment Analysis using RNN

A Deep Learning based NLP project that classifies movie reviews as **Positive** or **Negative** using a **Simple Recurrent Neural Network (RNN)**.  
This project also includes a **Streamlit web application** for real-time sentiment prediction.

---

## 🚀 Demo

Enter a movie review → Get instant sentiment prediction along with confidence score.

---

## 📌 Features

- 🧠 RNN-based text classification  
- 🔢 Embedding layer for semantic understanding  
- 📊 Binary output (Positive / Negative)  
- 🌐 Streamlit web app for user interaction  
- ⚡ Real-time prediction  

---

## 🧠 Model Architecture
Input Text
↓
Tokenization
↓
Padding (Fixed Length)
↓
Embedding Layer
↓
SimpleRNN Layer
↓
Dense Layer (Sigmoid)
↓
Output (Positive / Negative)

---

## 🗂️ Project Structure
├── embedding.ipynb # Text preprocessing & embedding/n
├── simplernn.ipynb # Model training
├── prediction.ipynb # Prediction pipeline
├── simple_rnn_imdb.h5 # Trained model
├── tokenizer.pkl/json # Tokenizer
├── app.py # Streamlit app
└── README.md # Project documentation


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Vansh-2102/RNN-imbd-movie-review-.git
cd RNN-imbd-movie-review-
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
streamlit run app.py

Input:

This movie was fantastic! The acting was great and the plot was thrilling.

Output:

Sentiment: Positive  
Prediction Score: 0.85+
