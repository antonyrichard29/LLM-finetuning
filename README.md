# Medical Symptom Assistant (LLM Fine-Tuning)

This is a lightweight medical symptom assistant created by fine-tuning the **TinyLlama-1.1B-Chat** language model using **LoRA (Low-Rank Adaptation)**.  
The project demonstrates how a large language model can be adapted to provide basic health guidance using a small, curated dataset.

# Model & Technique

- **Base Model:** TinyLlama-1.1B-Chat
- **Fine-tuning Method:** LoRA (Parameter-Efficient Fine-Tuning)
- **Frameworks Used:** Hugging Face Transformers, PEFT
- **Training Type:** Causal Language Modeling
- **Precision:** FP16 (GPU) / FP32 (CPU)

LoRA allows fine-tuning by training only small adapter layers instead of the full model, making the process fast and memory-efficient.
