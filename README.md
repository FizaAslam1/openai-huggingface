# NLP Project Solutions with Free Resources

This project demonstrates how to complete 10 NLP tasks using entirely free tools (Hugging Face, Google Colab, and Open Source models).

## 🛠️ Tools Used
- **Hugging Face Transformers** (Free models)
- **Google Colab** (Free GPU)
- **Sentence-Transformers** (For embeddings)
- **WordCloud** (For visualization)

## 📋 Task Solutions

### 1. Context Window in Language Models
**Solution:** Used GPT-2's 1024-token window as example
```python
from transformers import GPT2Tokenizer
tokenizer = GPT2Tokenizer.from_pretrained("gpt2")
print(f"Context window: {tokenizer.model_max_length} tokens")
