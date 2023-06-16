# LLM-Lora-PEFT_accumulate

Welcome to the **LLM-Lora-PEFT_accumulate** repository!

This repository contains implementations and experiments related to Large Language Models (LLMs) using **PEFT** (Parameter Efficient Fine Tuning), **LORA** (Low-Rank Adaptation of Large Language Models), and **QLORA** (Quantized LLMs with Low-Rank Adapters).

## Loading a model in 8-bit precision can save up to 4x memory compared to full precision model
![image](https://github.com/dasdristanta13/LLM-Lora-PEFT_accumulate/assets/70366198/d0e01c4a-da9d-46d9-9107-19d2865f8ec9)

## What does PEFT do?
You easily add adapters on a frozen 8-bit model thus reducing the memory requirements of the optimizer states, by training a small fraction of parameters

![image](https://github.com/dasdristanta13/LLM-Lora-PEFT_accumulate/assets/70366198/4869b64a-294c-4a23-8623-b17ee63a9f31)



## Resources

### 🌐 Websites

- [HF-BitsandBytes-Integration](https://huggingface.co/blog/hf-bitsandbytes-integration)
- [🤗 PEFT: Parameter-Efficient Fine-Tuning of Billion-Scale Models on Low-Resource Hardware](https://huggingface.co/blog/peft)
- [LLM.int8() and Emergent Features](https://timdettmers.com/2022/08/17/llm-int8-and-emergent-features/)
- [Tensorfloat-32-precision-format](https://blogs.nvidia.com/blog/2020/05/14/tensorfloat-32-precision-format/)
- [RLHF-LLM](https://huggingface.co/blog/trl-peft)

### 📺 YouTube Videos

- [Boost Fine-Tuning Performance of LLM: Optimal Architecture w/ PEFT LoRA Adapter-Tuning on Your GPU](https://youtu.be/A-a-l_sFtYM)
- [How to finetune your own Alpaca 7B](https://youtu.be/LSoqyynKU9E)

### 📄 Papers

- [PEFT: Parameter Efficient Fine Tuning](https://arxiv.org/pdf/2301.01821.pdf)
- [LORA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- [QLORA: Quantized LLMs with Low-Rank Adapters](https://arxiv.org/abs/2305.14314)
- [LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale](https://arxiv.org/pdf/2208.07339.pdf)
- [SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight Compression](https://arxiv.org/abs/2306.03078)

### 🐙 GitHub Repositories

- [TLoen Github Repo](https://github.com/tloen/alpaca-lora)

### 🐍 Python Notebooks

- [BitsAndBytes-4bit-Training](https://colab.research.google.com/drive/1VoYNfYDKcKRQRor98Zbf2-9VQTtGJ24k?usp=sharing)

## SWOT of LLMs

[![image](https://github.com/dasdristanta13/LLM-Lora-PEFT_accumulate/assets/70366198/18d3dc4a-499a-4cb1-a0c5-7b49fd0f2289)](SWOT.md)
Go to [LLM Analysis with SWOT](SWOT.md) for more clarification.
