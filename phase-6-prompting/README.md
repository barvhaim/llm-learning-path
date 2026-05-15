# Phase 6: Prompting & Reasoning (1-2 weeks)

## 🎯 Objectives
- Master advanced prompting techniques
- Understand reasoning capabilities and limitations
- Know how reasoning models (o1, R1) differ from standard LLMs

## 📄 Key Papers
- [ ] **[Chain-of-Thought Prompting (Wei et al., 2022)](https://arxiv.org/abs/2201.11903)** — "Let's think step by step"
- [ ] **[Self-Consistency (Wang et al., 2022)](https://arxiv.org/abs/2203.11171)** — Sample multiple reasoning paths, vote
- [ ] **[Tree of Thoughts (Yao et al., 2023)](https://arxiv.org/abs/2305.10601)** — Deliberate problem solving with search

## 📚 Core Topics

### Prompting Techniques
- [ ] Zero-shot vs. Few-shot prompting
- [ ] Chain-of-Thought (CoT) — explicit reasoning steps
- [ ] Self-Consistency — majority voting over CoT samples
- [ ] Tree of Thoughts — branching + backtracking
- [ ] ReAct — interleave reasoning with actions
- [ ] Structured prompts — system/user/assistant roles

### Reasoning Models
- [ ] OpenAI o1/o3 — test-time compute scaling
- [ ] DeepSeek R1 — open-source reasoning via GRPO
- [ ] Claude with extended thinking
- [ ] How "thinking tokens" work — internal chain of thought

### Prompt Engineering Best Practices
- [ ] Be specific and structured
- [ ] Provide examples (few-shot) for complex formats
- [ ] Use XML/JSON tags for structured input
- [ ] Constrain output format explicitly
- [ ] Temperature and top-p effects on generation

## 📄 Supplementary Papers
- [ ] [Let's Verify Step by Step (Lightman et al., 2023)](https://arxiv.org/abs/2305.20050) — Process reward models
- [ ] [Large Language Models are Zero-Shot Reasoners (Kojima et al., 2022)](https://arxiv.org/abs/2205.11916)
- [ ] [Reflexion (Shinn et al., 2023)](https://arxiv.org/abs/2303.11366) — Self-reflection for improvement

## 🛠️ Exercises
1. **Compare prompting strategies** — same task with zero-shot, few-shot, CoT
2. **Implement self-consistency** — sample N answers, pick majority
3. **Build a Tree of Thoughts solver** for a puzzle (e.g., Game of 24)
4. **Benchmark reasoning** — test different models on GSM8K math problems

## ✅ Phase Complete When
- [ ] Can choose the right prompting strategy for a given task
- [ ] Understand test-time compute scaling (why reasoning models "think longer")
- [ ] Have empirically compared different prompting techniques
