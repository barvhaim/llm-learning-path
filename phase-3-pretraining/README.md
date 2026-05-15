# Phase 3: Pre-training & Scaling (2-3 weeks)

## 🎯 Objectives
- Understand how LLMs are pre-trained at scale
- Learn about tokenization, training objectives, and scaling laws
- Know what makes training efficient (FlashAttention, distributed training)

## 📄 Key Papers
- [ ] **[Scaling Laws for Neural Language Models (Kaplan et al., 2020)](https://arxiv.org/abs/2001.08361)** — Fundamental scaling relationships
- [ ] **[Chinchilla — Training Compute-Optimal LLMs (Hoffmann et al., 2022)](https://arxiv.org/abs/2203.15556)** — Data vs. parameters tradeoff
- [ ] **[FlashAttention (Dao et al., 2022)](https://arxiv.org/abs/2205.14135)** — IO-aware exact attention

## 📚 Core Reading

### Tokenization
- [ ] BPE (Byte Pair Encoding) — how it works
- [ ] SentencePiece — language-agnostic tokenization
- [ ] tiktoken (OpenAI) — fast BPE implementation
- [ ] [Karpathy — "Let's Build the GPT Tokenizer"](https://www.youtube.com/watch?v=zduSFxRajkE)

### Training Objectives
- [ ] Causal Language Modeling (CLM) — GPT-style, predict next token
- [ ] Masked Language Modeling (MLM) — BERT-style, fill in blanks
- [ ] Prefix Language Modeling — encoder-decoder hybrid

### Scaling & Efficiency
- [ ] Scaling laws — loss as function of compute, data, parameters
- [ ] Chinchilla-optimal training — the right ratio
- [ ] Distributed training — Data Parallel, Tensor Parallel, Pipeline Parallel
- [ ] DeepSpeed ZeRO — memory-efficient training
- [ ] FSDP (Fully Sharded Data Parallel)
- [ ] Mixed-precision training (fp16, bf16)

## 📄 Supplementary Papers
- [ ] [GPT-3 (Brown et al., 2020)](https://arxiv.org/abs/2005.14165) — 175B parameters, few-shot learning
- [ ] [LLaMA (Touvron et al., 2023)](https://arxiv.org/abs/2302.13971) — Efficient open-source LLMs
- [ ] [LLaMA 2 (Touvron et al., 2023)](https://arxiv.org/abs/2307.09288) — Scaling + RLHF
- [ ] [Mistral 7B (Jiang et al., 2023)](https://arxiv.org/abs/2310.06825) — Efficient architecture choices
- [ ] [FlashAttention-2 (Dao, 2023)](https://arxiv.org/abs/2307.08691)

## 🛠️ Exercises
1. **Implement BPE tokenizer from scratch** — understand merge rules
2. **Train a small GPT with nanoGPT** — [github.com/karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)
3. **Experiment with scaling** — train models of different sizes, plot loss curves
4. **Profile GPU memory** — understand where memory goes in training

## ✅ Phase Complete When
- [ ] Can explain BPE tokenization step by step
- [ ] Understand the scaling laws and Chinchilla findings
- [ ] Know the tradeoffs of different distributed training strategies
- [ ] Have trained a model from scratch (even small)
