# 🔗 Generative AI Lab 10 – Sequential Data Generation

## 📌 Overview
This lab focuses on generating sequences using deep learning models. The goal is to learn patterns from sequential data and generate new sequences that follow similar structures.

---

## 🎯 Objective
- Implement generative models for sequential data  
- Understand sequence prediction using deep learning  
- Explore RNN, LSTM, and Transformer models  
- Generate new sequences from learned patterns  

---

## 🧠 What is Sequential Data Generation?
Sequential data generation is the process where a model learns from ordered data and predicts the next element in a sequence.

### Examples:
- Text sentences  
- Speech signals  
- Time-series data  
- Music generation  
- DNA sequences  

These models learn probability distributions and generate outputs step-by-step.

---

## ⚙️ Common Approaches
- Markov Models  
- N-gram Language Models  
- Recurrent Neural Networks (RNN)  
- LSTM / GRU Networks  
- Transformer Models  

---

# 🔹 Component I – LSTM Based Sequence Generation

## 📂 Dataset
A custom text dataset is used containing sentences related to AI, machine learning, and technology.

---

## 🔬 Tasks Performed
1. Loaded and preprocessed the dataset  
2. Applied character-level tokenization  
3. Created input-output sequence pairs  
4. Built an LSTM-based model  
5. Trained the model on text data  
6. Generated new sequences using seed input  

---

## 🧠 Model Used
- LSTM (Long Short-Term Memory)  
- Captures long-term dependencies in sequences  
- Processes data step-by-step  

---

## 🖼️ Output
- Generated meaningful text sequences  
- Maintained structure similar to training data  
- Demonstrated sequence learning capability  

---

# 🔹 Component II – Transformer Based Sequence Generation

## 🔬 Tasks Performed
1. Used the same dataset  
2. Applied tokenization  
3. Implemented positional encoding  
4. Built Transformer encoder model  
5. Trained model for sequence generation  

---

## 🧠 Model Used
- Transformer Encoder  
- Uses attention mechanism  
- Processes sequences in parallel  

---

## 🖼️ Output
- Generated more coherent sequences  
- Better handling of long-range dependencies  
- Faster training compared to LSTM  

---

## 📊 Comparison

| Feature        | LSTM                  | Transformer              |
|---------------|----------------------|--------------------------|
| Processing    | Sequential           | Parallel                 |
| Speed         | Slower               | Faster                   |
| Memory        | Uses hidden state    | Uses attention           |
| Performance   | Good                 | Better for long sequences|

---

