# Phase 4: Fine-Tuning & Alignment (2-3 weeks)

## 🎯 Objectives
- Understand SFT, RLHF, DPO, and GRPO
- Learn parameter-efficient fine-tuning (LoRA, QLoRA)
- Know how models go from "predicting text" to "following instructions"

## 📄 Key Papers
- [ ] **[InstructGPT — Training LMs to Follow Instructions (Ouyang et al., 2022)](https://arxiv.org/abs/2203.02155)** — The RLHF pipeline
- [ ] **[Constitutional AI (Bai et al., 2022)](https://arxiv.org/abs/2212.08073)** — RLAIF, harmlessness from AI feedback
- [ ] **[DPO — Direct Preference Optimization (Rafailov et al., 2023)](https://arxiv.org/abs/2305.18290)** — Simpler than RLHF
- [ ] **[LoRA — Low-Rank Adaptation (Hu et al., 2021)](https://arxiv.org/abs/2106.09685)** — Efficient fine-tuning
- [ ] **[GRPO — Group Relative Policy Optimization (DeepSeek, 2024)](https://arxiv.org/abs/2402.03300)** — RL without reward models

## 📚 Core Reading

### Supervised Fine-Tuning (SFT)
- [ ] Instruction tuning — formatting, chat templates
- [ ] Data quality > data quantity
- [ ] Evaluation during SFT — perplexity, benchmarks

### RLHF Pipeline
- [ ] Reward model training from human preferences
- [ ] PPO (Proximal Policy Optimization) for LM alignment
- [ ] KL divergence penalty — staying close to base model

### Modern Alignment
- [ ] DPO — why it's simpler (no separate reward model)
- [ ] GRPO — group-based relative rewards
- [ ] ORPO, SimPO, KTO — other recent alternatives
- [ ] Constitutional AI — self-supervision for safety

### Parameter-Efficient Fine-Tuning (PEFT)
- [ ] LoRA — low-rank weight updates
- [ ] QLoRA — quantized LoRA (4-bit base + LoRA)
- [ ] Adapters, Prefix Tuning (historical)

## 📄 Supplementary Papers
- [ ] [QLoRA (Dettmers et al., 2023)](https://arxiv.org/abs/2305.14314)
- [ ] [Zephyr — Direct Distillation (Tunstall et al., 2023)](https://arxiv.org/abs/2310.16944)
- [ ] [ORPO (Hong et al., 2024)](https://arxiv.org/abs/2403.07691)

## 🛠️ Exercises
1. **SFT a small model** with HuggingFace TRL on an instruction dataset
2. **Fine-tune with LoRA** — compare full fine-tuning vs. LoRA quality
3. **Run DPO training** on preference data
4. **Try Axolotl** — YAML-based fine-tuning: [github.com/axolotl-ai-cloud/axolotl](https://github.com/axolotl-ai-cloud/axolotl)
5. **Try Unsloth** — fast LoRA: [github.com/unslothai/unsloth](https://github.com/unslothai/unsloth)

## ✅ Phase Complete When
- [ ] Can explain the full RLHF pipeline (SFT → Reward Model → PPO)
- [ ] Understand why DPO is preferred over PPO in many cases
- [ ] Have fine-tuned a model with LoRA on custom data
- [ ] Know when to use full fine-tuning vs. LoRA vs. QLoRA
