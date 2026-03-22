<h1 align="center">Vibe Research Guide<br>Tools & Platforms</h1>

> From core Vibe Research platforms to supporting tools — find the right combination for your workflow.

---

## Core Vibe Research Platforms

Agent systems and platforms purpose-built for automated scientific research:

| Project | Focus | Link | Highlights |
|---|---|---|---|
| **InnoClaw** | AI research innovation agent | [GitHub](https://github.com/SpectrAI-Initiative/InnoClaw) | Open-source, literature analysis to idea generation |
| **ResearchClaw** | Personal research assistant | [GitHub](https://github.com/ymx10086/ResearchClaw) | Open-source, CLI/Web/Slack, integrated research/data/general tools |
| **FARS (Analemma)** | Fully automated research system | [GitHub](https://github.com/fars-analemma) · [Website](https://analemma.ai/) | Fudan MOSS team, 4 modules end-to-end (Ideation→Planning→Experiment→Writing) |
| **AI-Scientist** | End-to-end research automation | [GitHub](https://github.com/SakanaAI/AI-Scientist) | Sakana AI, idea→experiment→paper→review pipeline |
| **EvoScientist** | Self-evolving AI scientist | [GitHub](https://github.com/EvoScientist/EvoScientist) | Multi-agent with persistent memory, outperforms 7 SOTA systems |
| **Orchestra** | AI-for-Science platform | [Website](https://www.orchestra-research.com/) | Cloud-based, no local deployment needed |
| **Agent Laboratory** | Human-AI collaborative research | [GitHub](https://github.com/SamuelSchmidgall/AgentLaboratory) | Human-in-the-loop, researcher stays involved throughout |

### Related Claw Ecosystem Projects

| Project | Focus | Link | Highlights |
|---|---|---|---|
| **OpenClaw** | General-purpose personal AI assistant framework | [GitHub](https://github.com/openclaw/openclaw) · [Docs](https://docs.openclaw.ai/) | Cross-platform assistant with an extensible skill ecosystem |
| **ScienceClaw** | Self-evolving scientific research agent | [GitHub](https://github.com/beita6969/ScienceClaw) | Research-oriented Claw variant with persistent memory and evolving skills |
| **ScienceClaw (alt repo)** | Alternative research-lab implementation | [GitHub](https://github.com/Zaoqu-Liu/ScienceClaw) | Research workflow automation with broad database/tool coverage |
| **MetaClaw** | Self-evolving agent framework | [GitHub](https://github.com/aiming-lab/MetaClaw) · [Website](https://metaclaw.bot/) | Online learning framework for continuously improving Claw-style agents |
| **AutoResearchClaw** | Autonomous research pipeline | [GitHub](https://github.com/aiming-lab/AutoResearchClaw) | End-to-end academic pipeline from topic to paper with code, review, and reports |
| **ResearchClaw Desktop App** | Desktop paper reading and note-taking workflow | [Website](https://noietch.github.io/ResearchClaw/) | PDF chat, note-taking, agentic search, local-first workflow |

More ecosystem positioning: [→ Claw Park](./claw-park.md)

### Platform Comparison

| Dimension | InnoClaw | ResearchClaw | FARS | AI-Scientist | Orchestra |
|---|---|---|---|---|---|
| Open-source | ✅ | ✅ | ✅ | ✅ | ❌ (cloud) |
| Coverage | Literature→Idea | Literature→Data→Experiment | Idea→Paper (full) | Idea→Paper (full) | Full pipeline |
| Interface | CLI | CLI/Web/Slack | Web | CLI | Web |
| Difficulty | ⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐ |
| Best for | Beginners / Researchers | Individual researchers | Full automation | Full automation | Zero-code users |

### OpenClaw Ecosystem

[OpenClaw](https://docs.openclaw.ai/) is an open AI agent skill ecosystem with 28 skill categories (including AI & LLMs, search & research, agent social ecosystem), providing extensible skill support for the platforms above.

## Claw Park at a Glance

If you are confused by the growing number of Claw-branded projects, the cleanest mental model is:

| Layer | Representative project | Role |
|---|---|---|
| Foundation | OpenClaw | Base assistant framework and skill ecosystem |
| Research workspace | InnoClaw | Grounded workspace for files, papers, and execution |
| Personal research copilot | ResearchClaw | Day-to-day research assistance across search, notes, and writing |
| Scientific specialist | ScienceClaw | Research-oriented, self-evolving scientific collaborator |
| Evolution engine | MetaClaw | Learns skills from real conversations and improves over time |
| Autonomous pipeline | AutoResearchClaw | Turns an idea into a full paper pipeline with minimal human intervention |

Full guide: [→ Claw Park](./claw-park.md)

---

## Literature Discovery & Search

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| Semantic Scholar | [website](https://www.semanticscholar.org/) | Allen AI, AI-powered search, open API | Free |
| Connected Papers | [website](https://www.connectedpapers.com/) | Citation graph visualization | Free |
| Research Rabbit | [website](https://www.researchrabbit.ai/) | Continuous paper recommendations based on your collection | Free |
| Litmaps | [website](https://www.litmaps.com/) | Interactive literature maps | Free / Pro |
| Google Scholar | [website](https://scholar.google.com/) | Broadest coverage, supports Alerts | Free |

## Literature Reading & Synthesis

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| Elicit | [website](https://elicit.com/) | Enter a research question, auto-retrieve and extract data | Free |
| Consensus | [website](https://consensus.app/) | Evidence-based answers from papers | Free |
| NotebookLM | [website](https://notebooklm.google.com/) | Google, upload papers for conversational reading | Free |
| PaperQA2 | [GitHub](https://github.com/Future-House/paper-qa) | Open-source RAG literature Q&A with precise citations | Free |
| OpenScholar | [GitHub](https://github.com/allenai/OpenScholar) | Allen AI, large-scale literature synthesis | Free |
| Perplexity | [website](https://www.perplexity.ai/) | AI search engine with citations | Free |

## Deep Research Tools

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| OpenAI Deep Research | [website](https://openai.com/index/introducing-deep-research/) | Multi-step web research, structured reports, and cited synthesis | ChatGPT |
| Gemini Deep Research | [website](https://blog.google/products/gemini/google-gemini-deep-research/) | Google research copilot for broad web synthesis and planning | Gemini |
| Perplexity Deep Research | [website](https://www.perplexity.ai/) | Free, academic focus mode, multi-source synthesis | Free |
| Prism | [website](https://openai.com/prism/) | Scientific writing workspace for paper drafting, citations, and LaTeX-heavy workflows | Free |

## MCP Servers for Research

Model Context Protocol (MCP) servers that integrate academic search into AI workflows:

| Server | Link | Highlights |
|---|---|---|
| Semantic Scholar MCP | [GitHub](https://github.com/hamid-vakilzadeh/AIRA-SemanticScholar) | Search papers, analyze citations, paper recommendations |
| arXiv MCP Server | [GitHub](https://github.com/blazickjp/arxiv-mcp-server) | Search & retrieve arXiv papers with filtering by author, category, date |
| PubMed MCP Server | [PulseMCP](https://www.pulsemcp.com/) | Biomedical literature search and retrieval |

## Writing & Review Aids

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| Writefull | [website](https://www.writefull.com/) | AI proofreading designed for academic writing | Free / Pro |
| Paperpal | [website](https://paperpal.com/) | Backed by Springer Nature | Free / Pro |
| Grammarly | [website](https://www.grammarly.com/) | General writing assistant with academic mode | Free |
| OpenAI Prism | [website](https://openai.com/prism/) | OpenAI for Science — ChatGPT embedded in a scientific text editor | Free |

## Vibe Coding for Research

Research agents increasingly fail or succeed based on their **coding execution layer**: can they inspect repos, edit files safely, run experiments, and iterate on failures?

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| Claude Code | [Docs](https://docs.anthropic.com/en/docs/claude-code/overview) | Terminal-native coding agent with strong repo workflows, MCP support, and approval controls | Usage-based |
| Codex | [GitHub](https://github.com/openai/codex) | OpenAI coding agent for local and cloud task execution | Usage-based |
| Cursor Background Agents | [Docs](https://docs.cursor.com/en/background-agent) | Async remote agents for longer engineering tasks and parallel execution | Pro / Teams |
| GitHub Copilot Coding Agent | [Docs](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent) | Issue-to-PR workflow directly inside GitHub | Paid GitHub plan |
| Gemini CLI | [GitHub](https://github.com/google-gemini/gemini-cli) | Open-source terminal agent with Google Search grounding and MCP support | Free / usage-based |
| OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | Open-source full-stack agent platform with sandboxed execution | Free |

More workflow detail: [→ Vibe Coding](./vibe-coding.md)

## Experiment & Code Aids

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| Cursor | [website](https://cursor.sh/) | AI-native code editor | Free / Pro |
| GitHub Copilot | [website](https://github.com/features/copilot) | AI coding assistant | $10/mo |
| OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | Open-source full-stack agent | Free |
| SWE-agent | [GitHub](https://github.com/princeton-nlp/SWE-agent) | Code repair agent | Free |
| Weights & Biases | [website](https://wandb.ai/) | ML experiment tracking | Free (personal) |

## Reference Management

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| Zotero | [website](https://www.zotero.org/) | Open-source, rich ecosystem (AI plugins available) | Free |
| Zotero + ZoteroGPT | [GitHub](https://github.com/MuiseDestiny/zotero-gpt) | GPT plugin for Zotero | Free |
| Paperpile | [website](https://paperpile.com/) | Deep Google Docs integration | $3/mo |

## Adjacent Agentic Workflows

Not every useful "vibe" workflow is research. App prototyping, design iteration, slide generation, and knowledge work should stay in a separate lane so this repo does not blur core scientific automation with general-purpose creation.

| Tool | Link | Highlights | Cost |
|---|---|---|---|
| v0 | [website](https://v0.dev/docs) | Prompt-to-UI / app generation with code export and iteration | Free / usage-based |
| Lovable | [website](https://docs.lovable.dev/) | Product-builder workflow from prompt to deployed app with GitHub sync | Free / paid |
| Replit Agent | [Docs](https://docs.replit.com/replitai/agent) | In-browser agent for app building, debugging, and deployment | Free / paid |
| Figma AI | [website](https://www.figma.com/ai/) | Design ideation, Make-style prototyping, and interface generation | Paid |
| NotebookLM | [website](https://notebooklm.google/) | Source-grounded workspace for briefs, notes, and content synthesis | Free / paid |

Broader framing: [→ Vibe Anything](./vibe-anything.md)

---

## Tool Selection Guide

| What you want to do | Recommended |
|---|---|
| **Quick Vibe Research demo** | Elicit + NotebookLM (zero-code) |
| **Deploy a personal Research Agent** | InnoClaw or ResearchClaw |
| **Literature RAG Q&A** | PaperQA2 |
| **Full automated research** | FARS or AI-Scientist |
| **Cloud, no deployment** | Orchestra |
| **Complete research workflow** | ResearchClaw + Zotero + Cursor + W&B |
| **Researcher who also codes** | Deep Research + Claude Code or Codex + W&B |
| **Async issue-to-PR engineering** | Cursor Background Agents or GitHub Copilot Coding Agent |
| **Prompt-to-app prototyping** | v0 or Lovable |

---

> **Home**: [README](../README.md) · **Prev**: [Getting Started](./getting-started.md) · **Next**: [Surveys](./surveys.md)
