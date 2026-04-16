# 🧪 Lab 12: Generative Model with Attention (Chatbot)

## 📌 Course
CSET419 – Introduction to Generative AI

---

## 🎯 Objective
To implement a text generation model using **Attention Mechanism** to improve contextual understanding in chatbot responses.

---

## 🧠 Problem Statement
Build a chatbot that generates replies based on user input.  
The model uses **LSTM + Attention** to focus on important words in a sentence.

---

## 💡 Key Idea: Attention Mechanism
Attention assigns weights to input words so the model can focus more on relevant parts of the sentence.

👉 Example:
Input: `how are you`  
Output: `i am fine`  
✔ Attention focuses more on **"you"**

---

## ⚙️ Model Architecture
Embedding → Encoder (LSTM) → Attention → Decoder (LSTM) → Output Layer

---

## 📊 Dataset
For demonstration, a small dataset of conversation pairs is used:
