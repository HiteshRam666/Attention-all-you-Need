# 🚀 Transformer from Scratch — English to Hindi Translation

This repository implements a Transformer model **from scratch** (without using high-level libraries like `torch.nn.Transformer`) to translate sentences from English to Hindi.

---

## ✨ Highlights

- ✅ Full transformer architecture implemented from scratch (encoder, decoder, attention layers)
- ✅ Positional encoding
- ✅ Multi-head attention
- ✅ Masking (encoder self-attention mask, decoder self-attention mask, cross-attention mask)
- ✅ Greedy decoding
- ✅ Minimal dependencies (PyTorch only)

---

## 💡 Motivation

Transformers have revolutionized natural language processing by enabling parallelized training and capturing long-range dependencies effectively.

In this project, I wanted to **understand every internal working part**, so I built each component step by step instead of relying on pre-built modules.

---

## 🏗️ Architecture Overview

![images](https://github.com/user-attachments/assets/b9b58eb3-cc9b-4636-a30b-19daf3e7f7e6)


### Encoder

- Input embeddings + positional encoding
- Stacked multi-head self-attention layers
- Feedforward networks
- Layer normalization and residual connections

### Decoder

- Input embeddings + positional encoding
- Masked multi-head self-attention layers
- Encoder-decoder cross-attention
- Feedforward networks

### Output

- Generates Hindi tokens one by one using greedy decoding

---
