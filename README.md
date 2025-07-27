# Text-Summarisation-
📄✨ Fine-tuned T5-small model that transforms long news articles into crisp, human-like summaries.




The goal of this project is to create a deep learning model that can generate concise and meaningful summaries for lengthy news articles. By leveraging the powerful T5-small model from HuggingFace Transformers, we fine-tuned it to understand and summarize real-world news content effectively.

## 📚 Dataset

- **Size:** 5,266 rows
- **Structure:** Each entry contains:
  - `article`: Full news column
  - `summary`: Human-written summary
- Cleaned and preprocessed to optimize training and performance

## 🧠 Model

- **Architecture:** [T5-small](https://huggingface.co/t5-small)
- **Frameworks Used:** Hugging Face Transformers, PyTorch
- **Training Strategy:**
  - Tokenized using T5 tokenizer
  - Trained with teacher forcing on article-summary pairs
  - Early stopping and learning rate scheduling applied

## 🔍 Features

- Summarizes long-form news articles into concise abstracts
- Fine-tuned on real-world data
- Supports inference on custom inputs
- Modular codebase for easy experimentation
