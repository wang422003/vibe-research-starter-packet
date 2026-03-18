# Vibe Research 入门阅读清单

## 一、综述类

### 1. From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery

https://arxiv.org/abs/2505.13259

- 类型：Survey
- 推荐度：★★★★★
- 为什么读：建立全局框架，理解 LLM in Scientific Discovery 从 Tool -> Analyst -> Scientist 的演化
- 适合阶段：入门第一篇

### 2. LLM Agents as AI Scientists: A Survey

https://openreview.net/pdf?id=bfdUWy6rUA

- 类型：Survey
- 推荐度：★★★★★
- 为什么读：从科研全流程理解 agent，包括 hypothesis discovery、experiment implementation、paper writing、peer review
- 适合阶段：入门

### 3. A Survey of LLM-based Scientific Agents

https://arxiv.org/abs/2503.24047

- 类型：Survey
- 推荐度：★★★★☆
- 为什么读：更偏系统设计、benchmark、applications、ethics
- 适合阶段：入门到进阶过渡

---

## 二、代表性系统

### 4. The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery

https://arxiv.org/abs/2408.06292

- 类型：System
- 推荐度：★★★★★
- 为什么读：标志性工作，展示端到端科研自动化流程
- 关键词：AI Scientist, end-to-end research workflow

### 5. The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search

https://arxiv.org/abs/2504.08066?

- 类型：System
- 推荐度：★★★★★
- 为什么读：AI Scientist 的升级版，更高自主性，引入 agentic tree search
- 关键词：agentic tree search, autonomous science

### 6. Agent Laboratory: Using LLM Agents as Research Assistants

https://arxiv.org/abs/2501.04227

- 类型：System
- 推荐度：★★★★★
- 为什么读：更贴近 human-in-the-loop 的真实科研场景
- 关键词：research assistants, human feedback

---

## 三、Research Ideation

### 7. ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models

https://arxiv.org/abs/2404.07738

- 类型：Ideation
- 推荐度：★★★★★
- 为什么读：从文献出发迭代生成 idea，非常贴近“找 research gap → 提 idea”
- 关键词：research ideation, iterative refinement

### 8. Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers

https://arxiv.org/abs/2409.04109

- 类型：Evaluation / Ideation
- 推荐度：★★★★★
- 为什么读：大规模人类评估，研究 LLM ideas 的 novelty 与 feasibility
- 关键词：novelty, feasibility, human evaluation

### 9. Chain of Ideas: Revolutionizing Research Via Novel Idea Development with LLM Agents

https://arxiv.org/abs/2410.13185

- 类型：Ideation
- 推荐度：★★★★☆
- 为什么读：通过 Chain-of-Ideas 组织 literature，提升 idea generation
- 关键词：Chain-of-Ideas, Idea Arena

### 10. Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination

https://arxiv.org/abs/2409.14634

- 类型：Human-LLM Ideation
- 推荐度：★★★★☆
- 为什么读：强调 mixed-initiative ideation 与 novelty checking
- 关键词：facet recombination, novelty checking

---

## 四、Literature Synthesis

### 11. OpenScholar: Synthesizing Scientific Literature with Retrieval-Augmented Language Models

https://arxiv.org/abs/2411.14199

- 类型：RAG / Literature Synthesis
- 推荐度：★★★★★
- 为什么读：高质量 scientific literature synthesis 的代表工作
- 关键词：RAG, citation-backed synthesis

---

## 五、Benchmark / Evaluation

### 12. ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery

https://arxiv.org/abs/2410.05080

- 类型：Benchmark
- 推荐度：★★★★★
- 为什么读：严格评测 language agents 在 data-driven scientific discovery 中的能力
- 关键词：benchmark, scientific authenticity

### 13. FIRE-Bench: Evaluating Agents on the Rediscovery of Scientific Insights

https://arxiv.org/abs/2602.02905

- 类型：Benchmark
- 推荐度：★★★★★
- 为什么读：强调 rediscovery，关注“是否真的做出可验证科学发现”
- 关键词：rediscovery, verifiable discovery

### 14. AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite

https://arxiv.org/abs/2510.21652

- 类型：Benchmark
- 推荐度：★★★★☆
- 为什么读：更大规模、更 holistic 的 scientific research benchmark
- 关键词：holistic benchmark, scientific research suite

---

## 六、建议阅读顺序

1. From Automation to Autonomy
2. LLM Agents as AI Scientists
3. A Survey of LLM-based Scientific Agents
4. The AI Scientist
5. The AI Scientist-v2
6. Agent Laboratory
7. ResearchAgent
8. Can LLMs Generate Novel Research Ideas?
9. Chain of Ideas
10. Scideator
11. OpenScholar
12. ScienceAgentBench
13. FIRE-Bench
14. AstaBench