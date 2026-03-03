# Next-Gen Text Summarization with FLAN-T5 – PEFT & RLHF (AWS)

This project explores advanced fine-tuning strategies to improve dialogue summarization using **FLAN-T5**, focusing on accuracy, efficiency, and human-aligned safety.

The repository contains three progressive labs covering:
- Baseline summarization
- Parameter-Efficient Fine-Tuning (PEFT)
- Reinforcement Learning with Human Feedback (RLHF)

---

## 🚀 Project Overview

The goal of this project is to enhance dialogue summarization quality while ensuring computational efficiency and toxicity control.

We implement:

- **LoRA-based Parameter Efficient Fine-Tuning (PEFT)** to reduce training cost
- **Reinforcement Learning with Human Feedback (RLHF)** using PPO
- Toxicity reduction via reward modeling and evaluation
- Performance evaluation using ROUGE metrics

---

## 📂 Repository Structure
```text
GenAI/
│
├── Lab_1_summarize_dialogue.ipynb
├── Lab_2_fine_tune_generative_ai_model.ipynb
├── Lab_3_fine_tune_model_to_detoxify_summaries.ipynb
```


### Lab 1 – Baseline Dialogue Summarization
- Zero-shot and prompt-based summarization using FLAN-T5
- Evaluation using ROUGE metrics
- Establishes performance baseline

### Lab 2 – PEFT-Based Fine-Tuning (LoRA)
- Full fine-tuning vs Parameter Efficient Fine-Tuning
- Implemented **LoRA adapters** to reduce computational cost
- Optimized model weights while maintaining strong performance
- Evaluated improvements using ROUGE scores

### Lab 3 – RLHF for Toxicity-Controlled Summarization
- Implemented **Reinforcement Learning with PPO**
- Designed reward model for human-aligned summarization
- Integrated toxicity evaluation (Perspective API)
- Reduced harmful content while preserving summary quality

---

## 🧠 Key Concepts Implemented

- FLAN-T5 fine-tuning
- Parameter Efficient Fine-Tuning (LoRA)
- Reinforcement Learning with Human Feedback (RLHF)
- Proximal Policy Optimization (PPO)
- Reward modeling
- Toxicity evaluation
- ROUGE-based performance benchmarking

---

## 📊 Results

- Improved summarization accuracy over baseline
- Reduced training cost using LoRA
- Lower toxicity scores after RLHF fine-tuning
- Maintained concise and informative summaries

---

## 🛠 Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- PPO (RLHF)
- ROUGE
- Perspective API
- AWS (training environment)

---

## 🎯 Learning Outcomes

This project demonstrates:
- Practical LLM fine-tuning pipelines
- Human-alignment optimization using RLHF
- Evaluation and benchmarking of generative models
- Safe and efficient deployment strategies for LLM systems

---

## 📌 Disclaimer:
This project was completed as part of the “Generative AI with Large Language Models” course by DeepLearning.AI on AWS.
It has been extended and structured to highlight the implementation of PEFT and RLHF techniques for production-oriented LLM optimization.
