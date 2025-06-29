# LLMs From Scratch
This project implements three foundational types of Large Language Models (LLMs) from scratch using pure PyTorch. These models serve as a hands-on way to deeply understand the Transformer architecture and the training dynamics behind modern LLMs.

> [!TIP]
> Coding LLMs from first principles cultivates a deep understanding of how Transformer-based models actually work — from attention mechanics to pretraining strategies — and lays the foundation for fine-tuning open models for custom, domain-specific applications.

> [!CAUTION]
> Pre-training LLMs requires access to significant resources and is very expensive. For example, the GPT-3 pre-training cost is estimated to be $4.6 million in terms of cloud computing credits (https://mng.bz/VxEW).

> [!WARNING]
> - Models are small-scale (e.g., 6M–50M parameters) to allow for local training and debugging.
> - No distributed training or mixed-precision yet — though hooks are in place to support them.
> - Pretraining is compute-intensive. The purpose here is educational, not to compete with production models. Critical content demanding immediate user attention due to potential risks.

The goals is to build three types of LLMs from Scratch

- [ ] GPT-like LLM: An Autoregressive Decoder-only Generative Transformer Model
- [ ] BERT-like LLM: A Bidirectional Encoder-only Representation Transformer Model
- [ ] T5-like LLM: A Sequence-to-Sequence Encoder-Decoder Transformer Model
