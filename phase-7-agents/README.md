# Phase 7: LLM Agents (2-4 weeks) 🔥

## 🎯 Objectives
- Understand agent architectures (ReAct, tool use, memory, planning)
- Build agents that interact with external tools and APIs
- Know the current landscape of agent frameworks and applications

## 📄 Key Papers
- [ ] **[ReAct — Reasoning + Acting (Yao et al., 2022)](https://arxiv.org/abs/2210.03629)** — The foundational agent pattern
- [ ] **[Toolformer (Schick et al., 2023)](https://arxiv.org/abs/2302.04761)** — LLMs learning to use tools
- [ ] **[Generative Agents (Park et al., 2023)](https://arxiv.org/abs/2304.03442)** — Believable human behavior simulation
- [ ] **[Voyager (Wang et al., 2023)](https://arxiv.org/abs/2305.16291)** — Open-ended embodied agent
- [ ] **[SWE-Agent (Yang et al., 2024)](https://arxiv.org/abs/2405.15793)** — Software engineering agent
- [ ] **[A Survey on LLM-based Agents (Wang et al., 2024)](https://arxiv.org/abs/2401.05459)** — Comprehensive overview

## 📚 Core Topics

### Agent Architecture
- [ ] **Perception** — how agents receive input (text, images, tool outputs)
- [ ] **Reasoning** — CoT, planning, decomposition
- [ ] **Action** — tool calling, code execution, API interaction
- [ ] **Memory** — short-term (context window), long-term (vector DB), episodic
- [ ] **Reflection** — self-evaluation and correction

### Tool Use & Function Calling
- [ ] OpenAI function calling API
- [ ] Anthropic tool use
- [ ] [MCP (Model Context Protocol)](https://modelcontextprotocol.io/) — open standard for tool integration
- [ ] Building custom tools

### Agent Patterns
- [ ] ReAct loop — Thought → Action → Observation → repeat
- [ ] Plan-and-Execute — plan first, then execute steps
- [ ] Reflexion — learn from mistakes
- [ ] Multi-agent collaboration — agents talking to agents

### Agent Frameworks
- [ ] [LangChain](https://python.langchain.com/) / [LangGraph](https://langchain-ai.github.io/langgraph/)
- [ ] [CrewAI](https://www.crewai.com/) — multi-agent orchestration
- [ ] [AutoGen (Microsoft)](https://github.com/microsoft/autogen) — conversational agents
- [ ] [Hermes Agent](https://hermes-agent.nousresearch.com/) — personal agent OS with scheduler, memory, tools

### Real-World Agent Applications
- [ ] Coding agents — Claude Code, Codex CLI, Cursor, SWE-Agent
- [ ] Computer use — Claude Computer Use, Operator
- [ ] Research agents — literature review, data analysis
- [ ] Personal agents — email, calendar, task management

## 📚 Recommended Reading
- [ ] [Lilian Weng — LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)
- [ ] [Lilian Weng — Agent posts](https://lilianweng.github.io/tags/agent/)
- [ ] [Anthropic — Building Effective Agents](https://docs.anthropic.com/en/docs/build-with-claude/agent)
- [ ] [Andrew Ng — AI Agentic Design Patterns](https://www.deeplearning.ai/courses/)

## 📄 Supplementary Papers
- [ ] [HuggingGPT (Shen et al., 2023)](https://arxiv.org/abs/2303.17580) — LLM as controller for AI models
- [ ] [AutoGPT / BabyAGI (2023)](https://github.com/Significant-Gravitas/AutoGPT) — Early autonomous agents
- [ ] [LATS — Language Agent Tree Search (Zhou et al., 2023)](https://arxiv.org/abs/2310.04406)
- [ ] [Cognitive Architectures for Language Agents (Sumers et al., 2024)](https://arxiv.org/abs/2309.02427)

## 🛠️ Exercises
1. **Build a ReAct agent from scratch** — implement the Thought/Action/Observation loop
2. **Add tool calling** — calculator, web search, file I/O
3. **Implement memory** — conversation history + long-term retrieval
4. **Build a multi-agent system** — two agents collaborating on a task
5. **Create an MCP server** — expose a custom tool via MCP protocol
6. **Deploy a coding agent** — set up Claude Code or similar on a real codebase

## ✅ Phase Complete When
- [ ] Can design and implement a ReAct agent from scratch
- [ ] Understand the tradeoffs of different agent architectures
- [ ] Have built a working agent with tools and memory
- [ ] Know the current agent landscape (frameworks, products, research)
