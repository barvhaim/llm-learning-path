# Phase 2: Transformers (2-3 weeks)

## 🎯 Objectives
- Deeply understand the Transformer architecture
- Implement self-attention from scratch
- Know the difference between encoder, decoder, and encoder-decoder models

## 📄 Key Paper
- [ ] **[Attention Is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762)** — THE foundational paper

## 📚 Core Reading & Watching

### Understanding Attention
- [ ] [The Illustrated Transformer (Jay Alammar)](https://jalammar.github.io/illustrated-transformer/) — Best visual explanation
- [ ] [The Illustrated GPT-2 (Jay Alammar)](https://jalammar.github.io/illustrated-gpt2/) — Visualizing autoregressive generation
- [ ] [Karpathy — Let's Build GPT from Scratch (2hr video)](https://www.youtube.com/watch?v=KxOY0kjlSWo) — ⭐ Build a GPT step by step

### Architecture Deep-Dive
- [ ] Self-attention mechanism & scaled dot-product attention
- [ ] Multi-head attention — why multiple heads?
- [ ] Positional encoding — sinusoidal vs. learned vs. RoPE
- [ ] Layer normalization — Pre-LN vs. Post-LN
- [ ] Residual connections

### HuggingFace Course
- [ ] [HuggingFace LLM Course — Chapter 1](https://huggingface.co/learn/llm-course/en/chapter1/1)
- [ ] [HuggingFace Transformers Documentation](https://huggingface.co/docs/transformers/)

## 📄 Supplementary Papers
- [ ] [BERT (Devlin et al., 2018)](https://arxiv.org/abs/1810.04805) — Bidirectional encoder
- [ ] [GPT-2 (Radford et al., 2019)](https://arxiv.org/abs/2005.14165) — Autoregressive decoder
- [ ] [T5 (Raffel et al., 2019)](https://arxiv.org/abs/1910.10683) — Text-to-text framework

## 🛠️ Exercises
1. **Implement self-attention from scratch** in PyTorch (single head → multi-head)
2. **Follow Karpathy's "Let's Build GPT"** — code along and understand every line
3. **Fine-tune a small HuggingFace model** (e.g., DistilBERT) on a classification task
4. **Visualize attention patterns** — what does the model "look at"?

## ✅ Phase Complete When
- [ ] Can explain self-attention on a whiteboard
- [ ] Can implement multi-head attention from scratch
- [ ] Understand encoder vs. decoder vs. encoder-decoder architectures
- [ ] Comfortable using HuggingFace Transformers library
