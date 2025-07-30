# Few-Shot Prompting with Wekeza LLM v3 (DistilGPT2 + LoRA)

This notebook reimplements the few-shot prompting methodology introduced in the GPT-3 paper: ["Language Models are Few-Shot Learners"](https://arxiv.org/abs/2005.14165), applied to my fine-tuned domain-specific model — `distilgpt2-wekeza-finetuned_v3_lora`.

## 💡 What This Project Does
- Demonstrates **0-shot**, **1-shot**, and **few-shot** prompting.
- Applies these styles to real-world Kenyan financial assistant tasks like:
  - Money market fund summaries
  - Investment reporting
- Measures prompt effectiveness using qualitative outputs.

## 🔧 Model Used
- `distilgpt2-wekeza-finetuned_v3_lora` — a fine-tuned DistilGPT2 model trained with LoRA on Kenyan investment data.

## 📎 Related Paper
- [Language Models are Few-Shot Learners (Brown et al., 2020)](https://arxiv.org/abs/2005.14165)

## 📁 File
- `fewshot-prompting-wekeza-v3-gpt3style.ipynb`

## 🧪 Output
See the notebook for sample generations and comparisons between prompt types.

---

This is part of my ongoing hands-on NLP/LLM learning journey. Follow more on my [GitHub](https://github.com/Okoth67).
