# Multi-Language RL Model

This repository hosts a **Multi-Language Reinforcement Learning Model** using **Gradio** for an interactive UI. The model is based on **XLM-RoBERTa**, a multilingual transformer model for text classification.

## 🚀 Features
- Supports **multiple languages** for text classification.
- Uses **Gradio** for an easy-to-use web UI.
- **Runs on Hugging Face Spaces** with CPU (no API key needed).

## 📌 How to Use
1. **Enter text** in the provided input box.
2. **Model will classify** the text as `Correct` or `Incorrect`.
3. Works for **multiple languages**!

## 🛠️ Installation (For Local Development)
To run this model on your local machine:
```bash
git clone https://huggingface.co/spaces/SivaMallikarjun/multi-lang-rl-model
cd multi-lang-rl-model
pip install -r requirements.txt
python app.py
