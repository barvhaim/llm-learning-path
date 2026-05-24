# Phase 1: Foundations (2-3 weeks)

## 🎯 Objectives
- Understand neural network fundamentals (forward pass, backpropagation, gradient descent)
- Build intuition for embeddings and sequence models
- Know why Transformers replaced RNNs/LSTMs

## 📚 Core Reading & Watching

### Mathematics Refresher
- [ ] [3Blue1Brown — Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) — Visual intuition for vectors, matrices, eigenvalues
- [ ] [3Blue1Brown — Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) — Derivatives, chain rule, gradients
- [ ] [StatQuest — Probability Fundamentals](https://www.youtube.com/c/joshstarmer) — Bayes, distributions

### Neural Networks
- [ ] [3Blue1Brown — Neural Networks series](https://www.youtube.com/watch?v=I9v8efdO6vs) — Beautiful visual explanation
- [ ] [Karpathy — Neural Networks: Zero to Hero (Full Playlist)](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — Build everything from scratch in Python
  - Especially: "The spelled-out intro to neural networks and backpropagation"
  - And: "Building makemore" parts 1-5
- [ ] [Stanford CS231n — CNNs for Visual Recognition](https://www.youtube.com/playlist?list=PLoROMvodv4rOmsNzYBMe0gJY2XS8AQg16)

### Sequence Models (Historical Context)
- [ ] Understand word2vec / GloVe embeddings
- [ ] Understand RNN / LSTM limitations (vanishing gradients, sequential processing)
- [ ] [The Unreasonable Effectiveness of RNNs (Karpathy blog)](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

## 🛠️ Exercises
1. **Implement a simple neural network from scratch** (no PyTorch) — forward pass + backprop
2. **Train a character-level RNN** on a text dataset (follow Karpathy's makemore)
3. **Visualize embeddings** — train word2vec on a small corpus, plot with t-SNE

## ✅ Phase Complete When
- [ ] Can explain backpropagation without looking at notes
- [ ] Can implement a basic neural network in NumPy
- [ ] Understand why sequential processing in RNNs is a bottleneck
- [ ] Ready to understand why self-attention is revolutionary
