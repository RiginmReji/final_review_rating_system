# 🌟 Automatic Review Rating System

## 🧠 Project Overview
The Automatic Review Rating System predicts star ratings (1–5) from customer review text using a Bidirectional LSTM (BiLSTM) model.  
The system includes a Django backend, a frontend interface, and a trained deep learning model.

---

## 🚀 Features
- Predicts star ratings based on text input  
- Trained BiLSTM deep learning model  
- Django backend with integrated API  
- Frontend interface for user input and output display  

---

## 🗂️ Folder Structure



review-rating-system/
│
├── frontend/
│ ├── index.html
│ ├── style.css
│ └── script.js
│
├── backend/
│ ├── manage.py
│ ├── app/
│ │ ├── views.py
│ │ ├── urls.py
│ │ └── models.py
│ ├── model_BILSTM.h5
│ └── tokenizer.pkl
│
├── requirements.txt
└── README.md


🧩 Model Files

model_BILSTM.h5 – trained BiLSTM model
tokenizer.pkl – tokenizer used for text preprocessing


📊 Example Prediction
Review Text	Predicted Rating
Excellent product and great quality!	⭐⭐⭐⭐⭐
Poor quality and slow delivery.	⭐


📘 Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Django
Model: TensorFlow, Keras (BiLSTM)
Language: Python
