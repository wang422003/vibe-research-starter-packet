# Vibe Research Starter Packet

> A curated bilingual (CN/EN) starter packet for **Vibe Research**: LLM agents for scientific discovery, research ideation, literature synthesis, and scientific evaluation.
>
> 一个面向 **Vibe Research** 的中英双语入门资料包，聚焦 LLM Agent 在科学发现、研究构思、文献综合与科研评测中的代表性工作。

## Table of Contents

- [What is Vibe Research?](#what-is-vibe-research)
- [Who is this for?](#who-is-this-for)
- [Recommended Reading Path](#recommended-reading-path)
- [Legend](#legend)
- [Curated Reading List](#curated-reading-list)
  - [1) Surveys](#1-surveys)
  - [2) Representative Systems](#2-representative-systems)
  - [3) Research Ideation](#3-research-ideation)
  - [4) Literature Synthesis](#4-literature-synthesis)
  - [5) Benchmark and Evaluation](#5-benchmark-and-evaluation)
- [How to Contribute](#how-to-contribute)
- [Curation Principles](#curation-principles)
- [License](#license)

## What is Vibe Research?

**EN**: Vibe Research studies how LLM-based agents can support or automate the full research loop: finding ideas, planning experiments, writing code, synthesizing literature, and validating scientific insights.

**中文**：Vibe Research 关注 LLM Agent 如何支持或自动化完整科研流程：从 idea 发现、实验规划与实现，到文献综合和科研结论验证。

## Who is this for?

- Newcomers who want a structured entry point into AI-for-science agents
- Graduate students looking for paper-reading and project directions
- Builders who want to prototype research copilots or autonomous research systems

## Recommended Reading Path

If you are new, follow this path first:

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

## Legend

- **Recommendation**: `★★★★★` (must-read), `★★★★☆` (strongly recommended)
- **Stage**:
  - `Beginner`: first contact with the topic
  - `Beginner-Intermediate`: bridge to systems and methods
  - `Intermediate`: can support project design and implementation

## Curated Reading List

### 1) Surveys

| # | Paper | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|
| 1 | [From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery](https://arxiv.org/abs/2505.13259) | Survey | Global map of evolution from tool to analyst to scientist; excellent first paper. | Beginner | LLM4Science, evolution |
| 2 | [LLM Agents as AI Scientists: A Survey](https://openreview.net/pdf?id=bfdUWy6rUA) | Survey | Covers end-to-end pipeline: hypothesis, experiment, writing, and review. | Beginner | AI Scientist, lifecycle |
| 3 | [A Survey of LLM-based Scientific Agents](https://arxiv.org/abs/2503.24047) | Survey | Strong systems perspective: benchmark, architecture, applications, ethics. | Beginner-Intermediate | system design, benchmark |

### 2) Representative Systems

| # | Paper | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|
| 4 | [The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/abs/2408.06292) | System | Landmark end-to-end automation system for scientific discovery. | Intermediate | AI Scientist, workflow |
| 5 | [The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search](https://arxiv.org/abs/2504.08066) | System | Adds stronger autonomy with agentic tree search. | Intermediate | tree search, autonomy |
| 6 | [Agent Laboratory: Using LLM Agents as Research Assistants](https://arxiv.org/abs/2501.04227) | System | Practical human-in-the-loop setup for real-world research usage. | Intermediate | copilot, human feedback |

### 3) Research Ideation

| # | Paper | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|
| 7 | [ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models](https://arxiv.org/abs/2404.07738) | Ideation | Iterative idea generation grounded in literature and gap discovery. | Intermediate | ideation, iteration |
| 8 | [Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers](https://arxiv.org/abs/2409.04109) | Evaluation / Ideation | Large-scale human study on novelty and feasibility of generated ideas. | Intermediate | novelty, feasibility |
| 9 | [Chain of Ideas: Revolutionizing Research Via Novel Idea Development with LLM Agents](https://arxiv.org/abs/2410.13185) | Ideation | Organizes literature with Chain-of-Ideas and Idea Arena mechanisms. | Intermediate | Chain-of-Ideas, organization |
| 10 | [Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination](https://arxiv.org/abs/2409.14634) | Human-LLM Ideation | Mixed-initiative ideation and novelty checking via facet recombination. | Intermediate | mixed-initiative, novelty check |

### 4) Literature Synthesis

| # | Paper | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|
| 11 | [OpenScholar: Synthesizing Scientific Literature with Retrieval-Augmented Language Models](https://arxiv.org/abs/2411.14199) | RAG / Synthesis | Strong example of citation-backed scientific literature synthesis. | Intermediate | RAG, grounded synthesis |

### 5) Benchmark and Evaluation

| # | Paper | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|
| 12 | [ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery](https://arxiv.org/abs/2410.05080) | Benchmark | Rigorous evaluation for data-driven scientific discovery agents. | Intermediate | evaluation rigor, authenticity |
| 13 | [FIRE-Bench: Evaluating Agents on the Rediscovery of Scientific Insights](https://arxiv.org/abs/2602.02905) | Benchmark | Tests whether agents can rediscover verifiable scientific insights. | Intermediate | rediscovery, verification |
| 14 | [AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite](https://arxiv.org/abs/2510.21652) | Benchmark | Larger-scale and more holistic scientific research benchmark suite. | Intermediate | holistic benchmark, suite |

## How to Contribute

- Suggest a resource via GitHub Issue template: `Resource Suggestion`
- Submit updates through Pull Requests with complete metadata
- Follow criteria in [`docs/curation-guidelines.md`](docs/curation-guidelines.md)

## Curation Principles

We prioritize papers and resources that are:

1. Relevant to LLM agents in scientific workflows
2. Representative in methodology, scale, or influence
3. Clear about evaluation design and claims
4. Useful for newcomers building practical understanding

## License

MIT (see `LICENSE`).
