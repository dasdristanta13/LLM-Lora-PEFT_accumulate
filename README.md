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

## Contributing

We welcome contributions from researchers, developers, and enthusiasts. Feel free to share your experiments, optimizations, or new methods related to LLMs, PEFT, LORA, or QLORA.

To contribute, follow these steps:
1. Fork the repository and create a new branch for your work.
2. Implement your experiments or improvements.
3. Provide clear documentation and code explanations.
4. Test your implementation thoroughly.
5. Submit a pull request, explaining the purpose of your contribution.

Please respect the existing codebase's license and any third-party dependencies.

## Discussion

Join our discussions to exchange ideas, share experiences, and explore research directions. Here are some suggested topics:
- Comparing the performance and efficiency trade-offs of PEFT, LORA, and QLORA.
- Optimizing LLMs for specific NLP tasks.
- Further improving the efficiency of LLMs.

Remember to be respectful and considerate when engaging in discussions.

## Code of Conduct

Please adhere to our code of conduct, ensuring a positive and inclusive environment for all contributors and participants.

We look forward to your contributions and fruitful discussions!

Happy coding!  🚀
