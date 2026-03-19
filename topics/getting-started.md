<h1 align="center">Vibe Research Guide<br>Getting Started</h1>

> Get hands-on with Vibe Research in the shortest time — not by reading papers, but by using tools to do research.

## What is Vibe Research

Automate the research workflow with LLM Agents: literature review → idea generation → experiment design → code & run → paper writing.

You don't need to be an AI expert — you just need to use the right tools.

---

## Quick Start Routes

| Route | Time | Tools | What you can do |
|---|---|---|---|
| **Zero-code demo** | 5 min | Elicit / Consensus / NotebookLM | Search papers, read papers, ask questions with AI |
| **Deploy an agent** | 30 min | InnoClaw / ResearchClaw | Run a complete Research Agent |
| **Full automation** | 1–2 hrs | FARS (Analemma) | End-to-end: from idea to paper |

---

## Route 1: 5-Minute Zero-Code Demo

No coding required — experience Vibe Research with existing AI tools:

1. **Literature search**: Open [Elicit](https://elicit.com/), enter a research question (e.g., *"What are the main approaches for using LLMs in scientific discovery?"*), and see how AI retrieves papers and extracts key information
2. **Paper reading**: Upload a PDF to [NotebookLM](https://notebooklm.google.com/), ask *"Summarize the key contributions and limitations"*
3. **Idea brainstorm**: Enter your research direction in ChatGPT / Claude and let AI help you identify challenges and ideas

This is the basic form of Vibe Research — AI assisting every step of the research process.

---

## Route 2: Deploy a Research Agent in 30 Minutes

### Option A: InnoClaw (Recommended)

[InnoClaw](https://github.com/SpectrAI-Initiative/InnoClaw) is an open-source AI research agent focused on scientific innovation, supporting the full pipeline from literature analysis to idea generation.

```bash
# Clone the repo
git clone https://github.com/SpectrAI-Initiative/InnoClaw.git
cd InnoClaw

# Install dependencies
pip install -r requirements.txt

# Configure API Key
cp .env.example .env
# Edit .env and fill in your API Key

# Run
python main.py
```

What InnoClaw can do:
- Automated literature retrieval & analysis
- Literature-based idea generation
- Research plan design assistance

### Option B: ResearchClaw

[ResearchClaw](https://github.com/ymx10086/ResearchClaw) is a personal AI research assistant with CLI / Web / Slack interfaces.

```bash
git clone https://github.com/ymx10086/ResearchClaw.git
cd ResearchClaw

pip install -r requirements.txt

# Configure and run
python app.py
```

Core capabilities:
- **Research tools**: ArXiv search, Semantic Scholar retrieval, PDF parsing, BibTeX generation
- **Data tools**: Data analysis (pandas), visualization (matplotlib), statistical analysis
- **General tools**: Shell execution, file I/O, browser, memory management

Architecture: `User → Console/CLI/Slack → FastAPI → ScholarAgent (ReAct) → Tool suite`

### Option C: PaperQA2 (Literature Q&A)

[PaperQA2](https://github.com/Future-House/paper-qa) is ideal if you only need literature Q&A with RAG:

```bash
pip install paper-qa
export OPENAI_API_KEY="your-key"

python -c "
from paperqa import Docs
docs = Docs()
docs.add('your-paper.pdf')
answer = docs.query('What is the main contribution?')
print(answer.formatted_answer)
"
```

---

## Route 3: Full Automation

### FARS (Analemma) — Fully Automated Research System

[FARS](https://github.com/fars-analemma) (Fully Automated Research System) is developed by Analemma, a company founded by the Fudan MOSS team. It is currently the most complete end-to-end automated research system.

**Four modules**:

| Module | Function | Description |
|---|---|---|
| Ideation | Research ideation | Automatically discover research questions and novel ideas |
| Planning | Experiment planning | Design experiment plans and technical approaches |
| Experiment | Experiment execution | Automatically write code, run experiments, analyze results |
| Writing | Paper writing | Generate complete academic papers |

FARS conducted a 228-hour live demo, automatically producing 100 papers, demonstrating the feasibility of full-pipeline automation.

Website: [analemma.ai](https://analemma.ai/) · GitHub: [fars-analemma](https://github.com/fars-analemma)

### AI-Scientist — End-to-End Research

[AI-Scientist](https://github.com/SakanaAI/AI-Scientist) by Sakana AI covers idea generation → experiment → paper writing → automated review.

```bash
git clone https://github.com/SakanaAI/AI-Scientist.git
cd AI-Scientist
pip install -r requirements.txt
export OPENAI_API_KEY="your-key"
```

### Orchestra — AI-for-Science Platform

[Orchestra](https://www.orchestra-research.com/) is an AI-for-Science platform designed for Vibe Research, offering cloud-based research automation with no local deployment required.

---

## Tool Selection Guide

| What you want to do | Recommended tool | Difficulty |
|---|---|---|
| Quickly search & read papers | Elicit / Consensus / NotebookLM | ⭐ |
| Run a Research Agent | InnoClaw / ResearchClaw | ⭐⭐ |
| Literature Q&A with RAG | PaperQA2 | ⭐⭐ |
| Full automation (idea → paper) | FARS / AI-Scientist | ⭐⭐⭐ |
| Cloud research platform | Orchestra | ⭐ |

---

## FAQ

**Q: Do I need to know programming?**
A: Not necessarily. Zero-code tools (Elicit, NotebookLM, Orchestra) cover basic scenarios. Deploying an agent requires basic Python and command line skills.

**Q: Do I need a GPU?**
A: Most tools use API calls — a regular laptop is fine. A GPU is only needed for local model deployment.

**Q: How much do API calls cost?**
A: Small-scale experiments cost about $1–5. Set token limits and test with small data first.

**Q: Can AI-assisted research be published?**
A: Yes, but check each venue's policy on AI-assisted writing. Core principle: the researcher is responsible for the content.

---

> **Home**: [README](../README.md) · **Next**: [Tools & Platforms](./tools.md)
