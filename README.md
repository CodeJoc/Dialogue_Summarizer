# 📝 Dialogue Summarization using T5 

This project fine-tunes the **T5 Transformer model** for abstractive **dialogue summarization**, using the **SAMSum dataset**. It allows users to input casual conversations (like WhatsApp or Messenger chats) and generates concise summaries.

## 🚀 Features

- Fine-tunes `T5-small` for summarizing human dialogues.
- Preprocessing using HuggingFace Datasets & Tokenizers.
- Saves and loads fine-tuned model from disk.
- Generates summaries for new user conversations.

## 🧠 Model Info

- **Model:** [t5-small](https://huggingface.co/t5-small)
- **Fine-tuned using:** Hugging Face's `Trainer` API
- **Training Details:**
  - Epochs: 3–5
  - Batch Size: 8–16
