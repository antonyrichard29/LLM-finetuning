# HealthMate – Medical Symptom Assistant (LLM Fine-Tuning)

HealthMate is a lightweight medical symptom assistant created by fine-tuning the **TinyLlama-1.1B-Chat** language model using **LoRA (Low-Rank Adaptation)**.  
The project demonstrates how a large language model can be adapted to provide basic health guidance using a small, curated dataset.

⚠️ This project is for **educational purposes only** and does **not replace professional medical advice**.

---

## 🚀 Features

- Fine-tuned **TinyLlama-1.1B-Chat** using LoRA (PEFT)
- Works on **CPU and GPU** (Google Colab compatible)
- Handles common symptoms like fever, headache, cough, stomach pain, dizziness, etc.
- Lightweight dataset (≈50 samples)
- Efficient training with minimal compute resources
- Interactive command-line interface for testing

---

## 🧠 Model & Technique

- **Base Model:** TinyLlama-1.1B-Chat
- **Fine-tuning Method:** LoRA (Parameter-Efficient Fine-Tuning)
- **Frameworks Used:** Hugging Face Transformers, PEFT
- **Training Type:** Causal Language Modeling
- **Precision:** FP16 (GPU) / FP32 (CPU)

LoRA allows fine-tuning by training only small adapter layers instead of the full model, making the process fast and memory-efficient.
