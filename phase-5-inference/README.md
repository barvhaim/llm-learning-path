# Phase 5: Inference & Deployment (1-2 weeks)

## 🎯 Objectives
- Understand quantization methods and tradeoffs
- Know how to serve LLMs efficiently
- Benchmark throughput, latency, and quality

## 📚 Core Topics

### Quantization
- [ ] Why quantize? Memory vs. quality tradeoffs
- [ ] GPTQ — post-training quantization (GPU)
- [ ] GGUF — CPU-friendly quantization (llama.cpp)
- [ ] AWQ — activation-aware quantization
- [ ] bitsandbytes — 4-bit/8-bit for training & inference
- [ ] FP8, INT4 — hardware-native quantization

### Inference Optimization
- [ ] KV-Cache — why it matters, memory implications
- [ ] Continuous batching — maximize throughput
- [ ] Speculative decoding — use small model to draft, large to verify
- [ ] PagedAttention (vLLM) — virtual memory for KV-cache
- [ ] Prefix caching — reuse common prefixes

### Serving Frameworks
- [ ] [vLLM](https://github.com/vllm-project/vllm) — high-throughput serving, PagedAttention
- [ ] [llama.cpp](https://github.com/ggml-org/llama.cpp) — CPU/GPU inference, GGUF format
- [ ] [TGI (Text Generation Inference)](https://github.com/huggingface/text-generation-inference) — HuggingFace's serving solution
- [ ] [Ollama](https://ollama.ai/) — easy local model serving
- [ ] [SGLang](https://github.com/sgl-project/sglang) — structured generation + serving

### Structured Output
- [ ] JSON mode / function calling
- [ ] [Outlines](https://github.com/dottxt-ai/outlines) — guaranteed structured generation
- [ ] Grammar-constrained decoding

## 🛠️ Exercises
1. **Quantize a 7B model** to GGUF (Q4_K_M, Q5_K_M) — compare quality
2. **Serve with vLLM** — benchmark requests/sec with different batch sizes
3. **Run llama.cpp** — test CPU vs. GPU inference speed
4. **Compare quantization levels** — run same prompts on FP16/INT8/INT4, measure quality

## ✅ Phase Complete When
- [ ] Can explain GPTQ vs. GGUF vs. AWQ tradeoffs
- [ ] Have served a model with vLLM and measured throughput
- [ ] Understand KV-cache memory scaling and optimization strategies
- [ ] Know when to use which serving framework
