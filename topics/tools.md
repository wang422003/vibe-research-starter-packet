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
| **FutureHouse Platform** | Scientific agent platform | [Website](https://www.futurehouse.org/research-announcements/launching-futurehouse-platform-ai-agents?_bhlid=b2b50af9254da4cf97bbad70959795fa728b14f6) | Public platform for specialized science agents and API-style workflows |
| **Edison Scientific** | AI scientist platform for R&D teams | [Website](https://edisonscientific.com/) · [Kosmos](https://edisonscientific.com/articles/announcing-kosmos) | Commercial scientific-discovery platform with private-data and enterprise workflow focus |

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

[OpenClaw](https://docs.openclaw.ai/) is an open AI agent skill ecosystem spanning assistant, research, search, and workflow capabilities, providing extensible skill support for the platforms above.

### OpenClaw In 2026 Spring

The strongest current signal is that OpenClaw is no longer just a single assistant shell:

- It has a public skill-discovery layer through [ClawHub](https://docs.openclaw.ai/tools/clawhub).
- It is pushing cross-ecosystem installability through [Plugin Bundles](https://docs.openclaw.ai/plugins/bundles), including compatibility paths for other coding-agent ecosystems.
- Its value is increasingly in acting as a gateway, distribution layer, and control surface for broader agent workflows.

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

## Plugins, Bridges & Registries

The stack is no longer just "pick an agent." A new layer of bridges, plugin surfaces, and registries now determines how easily a research workflow can be extended and operated.

| Resource | Link | What it adds | Why it matters |
|---|---|---|---|
| **cc-connect** | [GitHub](https://github.com/chenhg5/cc-connect) | Bridges Claude Code, Cursor, Gemini CLI, Codex, Goose, and more into chat apps | Useful when teams want to run coding or research agents from Feishu/Lark, Slack, Telegram, or WeCom instead of a local terminal |
| **ClawHub** | [Docs](https://docs.openclaw.ai/tools/clawhub) | Public discovery surface for OpenClaw-compatible skills and tools | Shows OpenClaw moving toward a real skill-distribution layer rather than a closed assistant |
| **OpenClaw Plugin Bundles** | [Docs](https://docs.openclaw.ai/plugins/bundles) | Compatible bundles for importing capabilities across agent ecosystems | Useful for understanding how agent ecosystems may converge through bundle compatibility instead of isolated plugin silos |
| **Claude Code extensibility** | [Docs](https://docs.anthropic.com/en/docs/claude-code/settings) | Official hooks, slash commands, subagents, and MCP integration surfaces | Defines the plugin/customization model around one of the most common terminal agents |
| **awesome-claude-code-plugins** | [GitHub](https://github.com/ccplugins/awesome-claude-code-plugins) | Curated list of Claude Code prompts, commands, hooks, subagents, and MCP servers | Fastest way to see how the Claude Code plugin layer is evolving in practice |
| **MCP Registry** | [Website](https://modelcontextprotocol.io/registry/about) | Official discovery and installation surface for MCP servers | Reduces friction when testing or installing new tool integrations |
| **awesome-mcp-servers** | [GitHub](https://github.com/punkpeye/awesome-mcp-servers) | Broad discovery map of the MCP ecosystem | One of the highest-signal indexes for scouting connectors quickly |
| **awesome-openclaw-skills** | [GitHub](https://github.com/sundial-org/awesome-openclaw-skills) | Community-curated OpenClaw skill directory | Shows the skill-distribution layer growing around the Claw ecosystem |

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

## AI Scientist Platforms & Current Signals

One of the clearest 2026 shifts is that AI-scientist systems are no longer only papers or repos. They are becoming public platforms, products, and applied benchmarks.

| Signal | Link | Why it matters |
|---|---|---|
| **FutureHouse Platform** | [Website](https://www.futurehouse.org/research-announcements/launching-futurehouse-platform-ai-agents?_bhlid=b2b50af9254da4cf97bbad70959795fa728b14f6) | Shows the public-platform direction for specialized scientific agents, not just one-off demos |
| **Robin** | [Announcement](https://www.futurehouse.org/research-announcements/demonstrating-end-to-end-scientific-discovery-with-robin-a-multi-agent-system) | High-signal end-to-end demonstration of multi-agent scientific discovery and validated wet-lab-style workflow claims |
| **BixBench** | [Announcement](https://www.futurehouse.org/research-announcements/bixbench) | Signals that more realistic, domain-specific benchmarks are becoming central to evaluating research agents |
| **Edison Scientific / Kosmos** | [Website](https://edisonscientific.com/) · [Kosmos](https://edisonscientific.com/articles/announcing-kosmos) | Shows how AI-scientist ideas are being packaged into persistent scientific-discovery platforms for real R&D teams |

## Learning, RL & Self-Evolving Agents

The stack is no longer only "tool-using agents." A distinct learning layer is forming around training, online improvement, skill extraction, and persistent memory.

| Resource | Link | What it does | Why it matters |
|---|---|---|---|
| **Agent Lightning** | [GitHub](https://github.com/microsoft/agent-lightning) | Trains arbitrary agents with RL, automatic prompt optimization, and SFT with minimal code changes | Strongest current signal that agent training is becoming framework-agnostic infrastructure |
| **Agent0** | [GitHub](https://github.com/aiming-lab/Agent0) | Zero-data self-evolving language and vision-language agents through tool-integrated reasoning | Useful reference for agents that generate their own training signal instead of relying on curated datasets |
| **AgentEvolver** | [GitHub](https://github.com/modelscope/AgentEvolver) | End-to-end self-evolving training system with self-questioning, self-navigating, and self-attributing | Good mental model for how exploration, experience reuse, and credit assignment can be unified |
| **EvoAgentX** | [GitHub](https://github.com/EvoAgentX/EvoAgentX) | Framework for building, evaluating, and evolving agentic workflows | Pushes the field from single-prompt tuning toward workflow-level evolution |
| **Acontext** | [GitHub](https://github.com/memodb-io/Acontext) | Context and memory platform that turns sessions into persistent skills and reusable operating knowledge | Shows how memory and skill accumulation are becoming part of the agent-improvement stack |
| **Awesome-Self-Evolving-Agents** | [GitHub](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents) | Survey-style map of self-evolving agents and optimization methods | Best compact overview when you want the broader literature and repo landscape, not only one framework |

## Research MCP Servers & Academic Connectors

Model Context Protocol (MCP) servers that integrate academic search into AI workflows:

| Server | Link | Highlights |
|---|---|---|
| Semantic Scholar MCP | [GitHub](https://github.com/hamid-vakilzadeh/AIRA-SemanticScholar) | Search papers, analyze citations, paper recommendations |
| OpenAlex Research MCP | [GitHub](https://github.com/oksure/openalex-research-mcp) | OpenAlex-powered literature search, citation graph exploration, and research trend analysis |
| Academia MCP | [GitHub](https://github.com/IlyaGusev/academia_mcp) | Aggregates arXiv, ACL Anthology, Semantic Scholar, and academic search into one MCP surface |
| PapersWithCode MCP | [GitHub](https://github.com/hbg/mcp-paperswithcode) | Bridges papers to code repos, datasets, tasks, methods, and leaderboard context |
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
| **Need a public science-agent platform** | FutureHouse Platform |
| **Need a commercial AI-scientist platform for team workflows** | Edison Scientific / Kosmos |
| **Operate agents from team chat** | cc-connect |
| **Scout new connectors quickly** | MCP Registry or awesome-mcp-servers |
| **Literature RAG Q&A** | PaperQA2 |
| **Need literature plus benchmark/code metadata** | OpenAlex Research MCP + PapersWithCode MCP |
| **Need agent training / optimization** | Agent Lightning |
| **Need self-evolving agent infrastructure** | Agent0 or AgentEvolver |
| **Need persistent skill / context memory** | Acontext |
| **Full automated research** | FARS or AI-Scientist |
| **Cloud, no deployment** | Orchestra |
| **Complete research workflow** | ResearchClaw + Zotero + Cursor + W&B |
| **Researcher who also codes** | Deep Research + Claude Code or Codex + W&B |
| **Async issue-to-PR engineering** | Cursor Background Agents or GitHub Copilot Coding Agent |
| **Prompt-to-app prototyping** | v0 or Lovable |

---

> **Home**: [README](../README.md) · **Prev**: [Getting Started](./getting-started.md) · **Next**: [Surveys](./surveys.md)
