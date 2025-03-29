# 🚀 LLaMA 3.1 / Mistral / TinyLlama Fine-Tuning Pipeline

This repository provides an **interactive fine-tuning pipeline** for **LLaMA 3.1**, **Mistral v0.3**, and **TinyLlama**, using **Hugging Face Transformers** and **PyTorch**. The pipeline allows users to select a model via a dropdown and fine-tune it on a dataset.

## 📌 Features
- ✅ **Supports multiple models** (LLaMA 3.1, Mistral v0.3, TinyLlama).  
- ✅ **Interactive dropdown for model selection**.  
- ✅ **Automatic model loading & fine-tuning**.  
- ✅ **Memory-optimized training using 8-bit mode**.  
- ✅ **Resumes downloads to prevent interruptions**.  
- ✅ **Supports GPU acceleration with `torch.bfloat16`**.  

---

## 📥 Installation
Ensure you have the necessary dependencies installed:
```bash
pip install transformers datasets torch ipywidgets
If using Hugging Face private models, authenticate:
```

```bash
huggingface-cli login
```
## ⚡ Supported Models
|Model| Hugging Face ID|
|LLaMA 3.1 (8B)|	meta-llama/Llama-3.1-8B-Instruct|
|Mistral v0.3 (7B)|	mistralai/Mistral-7B-Instruct-v0.3|
|TinyLlama 1.1B|	TinyLlama/TinyLlama-1.1B-chat-v1.0|

## 🚀 Training Optimization
This pipeline leverages memory-efficient techniques to optimize fine-tuning performance:

- ✅ torch.bfloat16 → Uses mixed precision for speed.

- ✅ resume_download=True → Continues interrupted downloads.

- ✅ device_map="auto" → Automatically assigns model to the best available GPU.

## 📜 License
This project is licensed under the MIT License.

## 👨‍💻 Author
Developed by Team synαpse. If you have any questions, feel free to reach out!

