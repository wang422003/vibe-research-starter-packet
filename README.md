<h1 align="center">Vibe Research Guide</h1>

<p align="center">
  <em>A curated guide for LLM-agent-driven scientific research automation</em>
</p>

<p align="center">
  <a href="https://github.com/SpectrAI-Initiative/Vibe-Research-Guide/stargazers"><img src="https://img.shields.io/github/stars/SpectrAI-Initiative/Vibe-Research-Guide?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/SpectrAI-Initiative/Vibe-Research-Guide/commits/main"><img src="https://img.shields.io/github/last-commit/SpectrAI-Initiative/Vibe-Research-Guide?style=flat-square" alt="Last Commit"></a>
  <a href="https://github.com/SpectrAI-Initiative/Vibe-Research-Guide/issues"><img src="https://img.shields.io/github/issues/SpectrAI-Initiative/Vibe-Research-Guide?style=flat-square" alt="Issues"></a>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="MIT">
</p>

<p align="center">
  <strong><a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/SpectrAI-Initiative/Vibe-Research-Guide/main/index.html">🌐 View Interactive Multilingual README →</a></strong><br>
  <small>🇨🇳 中文 · 🇺🇸 English · 🇰🇷 한국어 · 🇯🇵 日本語 · 🇩🇪 Deutsch · 🇫🇷 Français · 🇪🇸 Español · 🇮🇹 Italiano · 🇵🇹 Português · 🇸🇦 العربية · 🇹🇭 ไทย · 🇻🇳 Tiếng Việt · 🇷🇺 Русский</small>
</p>

<p align="center">
  <img src="files/images/vibe_research_guide_image_1.png" alt="Vibe Research Guide Overview" width="90%">
</p>

---

<div align="center">

### AI Agents For Scientific Discovery, Research Execution, And The New Claw Ecosystem

Automate the research loop with LLM agents: literature review → idea generation → experiment execution → paper writing → peer review.

This repo is a **landing page for the field**: use it to choose the right track, then move into the topic pages for detail.

**Start here**: [Getting Started](./topics/getting-started.md) · [Tools & Platforms](./topics/tools.md) · [Claw Park](./topics/claw-park.md) · [Vibe Coding](./topics/vibe-coding.md)

</div>

<p align="center">
  <img src="files/images/_34_Vibe_Research_AI_assistant_idealiteratureexperimentcoderesultpaperLLM_based_agents__image_1.png" alt="Vibe Research: AI assistant workflow (idea → literature → experiment → code → result → paper)" width="85%">
</p>

## At A Glance

<table>
  <tr>
    <td width="33%">
      <strong>Core Question</strong><br><br>
      How far can AI move from research assistant to research operator?<br><br>
      Focus: literature, ideation, experiment, writing, and evaluation.
    </td>
    <td width="33%">
      <strong>What Changed In 2026</strong><br><br>
      Research copilots got stronger, learning layers became real, autonomous research systems got more credible, and Vibe Coding became the execution layer.
    </td>
    <td width="33%">
      <strong>How To Use This Repo</strong><br><br>
      Treat the README as a map. Treat the topic pages as the actual guide.
    </td>
  </tr>
</table>

## 2026 Landscape Snapshot

Four trends are now shaping the field:

1. **Research copilots are getting stronger**: Deep Research products, NotebookLM-style source-grounded reading, and scientific workspaces such as Prism are making literature synthesis and report writing much faster.
2. **Learning and self-evolving agents are becoming a real layer**: Agent Lightning, Agent0, AgentEvolver, EvoAgentX, and memory substrates such as Acontext suggest that training, optimization, and persistent reusable experience are becoming first-class agent infrastructure.
3. **Autonomous research systems are maturing**: AI Scientist-v2, Agent Laboratory, and EvoScientist push the field from "paper summary bots" toward iterative ideation, execution, and evaluation.
4. **Vibe Coding is becoming the execution layer**: terminal agents, coding agents, and background agents now matter because research automation increasingly depends on reliable code generation, experiment loops, and repository operations.

This guide keeps **Vibe Research** as the core topic, then adds separate sections for **Vibe Coding** and **Vibe Anything** so the repo can expand without losing scope.

---

## 2026 Spring Signals

Several current signals make the field feel less like a loose collection of demos and more like an emerging stack:

1. **Learning and RL are becoming a first-class layer**: [Agent Lightning](https://github.com/microsoft/agent-lightning) turns arbitrary agents into trainable systems with RL, automatic prompt optimization, and SFT; [Agent0](https://github.com/aiming-lab/Agent0) and [AgentEvolver](https://github.com/modelscope/AgentEvolver) push zero-data and self-generated evolution; [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX) and [EvoScientist](https://github.com/EvoScientist/EvoScientist) push evolving workflows and scientist loops.
2. **Skill and memory are becoming learning substrates**: [Acontext](https://github.com/memodb-io/Acontext) and [anthropics/skills](https://github.com/anthropics/skills) suggest that reusable skills, persistent context, and accumulated experience are becoming part of the agent learning stack rather than only convenience features.
3. **OpenClaw is becoming a platform layer**: it now reads more like a self-hosted gateway plus control UI plus skill registry plus compatible plugin-bundle layer than a single assistant app. See [OpenClaw](https://docs.openclaw.ai/), [ClawHub](https://docs.openclaw.ai/tools/clawhub), and [Compatible Bundles](https://docs.openclaw.ai/plugins/bundles).
4. **FutureHouse and Edison show platformization**: [FutureHouse Platform](https://www.futurehouse.org/research-announcements/launching-futurehouse-platform-ai-agents?_bhlid=b2b50af9254da4cf97bbad70959795fa728b14f6), [Robin](https://www.futurehouse.org/research-announcements/demonstrating-end-to-end-scientific-discovery-with-robin-a-multi-agent-system), [BixBench](https://www.futurehouse.org/research-announcements/bixbench), [Edison](https://edisonscientific.com/), and [Kosmos](https://edisonscientific.com/articles/announcing-kosmos) show how the field is moving from repos and papers to persistent public or commercial platform surfaces.
5. **Execution and connectors remain the glue**: MCP registries, routing layers, plugin bundles, and research connectors still determine whether these agents can actually plug into code, literature, chat surfaces, and scientific databases.

---

## Learning, RL & Self-Evolving Agents

This is the layer the guide used to underweight: not just tool-using agents, but agents that can be trained, optimized, or improved over time.

| Layer | Representative resources | Why it matters |
|---|---|---|
| **Agent training / optimization** | [Agent Lightning](https://github.com/microsoft/agent-lightning) | Brings RL, automatic prompt optimization, and SFT to arbitrary agent systems with near-zero code changes |
| **Zero-data self-evolution** | [Agent0](https://github.com/aiming-lab/Agent0) · [AgentEvolver](https://github.com/modelscope/AgentEvolver) | Shows how agents can generate tasks, feedback, and training signals without human-curated data pipelines |
| **Evolving workflows** | [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX) · [EvoScientist](https://github.com/EvoScientist/EvoScientist) · [MetaClaw](https://github.com/aiming-lab/MetaClaw) | Shifts the focus from optimizing one prompt to evolving whole workflows, skill graphs, or scientist loops |
| **Skill & memory substrate** | [Acontext](https://github.com/memodb-io/Acontext) · [anthropics/skills](https://github.com/anthropics/skills) | Makes skills, context, and reusable experience part of the learning layer |
| **Landscape map** | [Awesome-Self-Evolving-Agents](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents) | Best current GitHub-native overview of the optimization, evolution, and lifelong-agent literature |

---

## Execution, Skills & Agent Ops

The execution layer is still where the fastest open-source productization is happening:

1. **Skills marketplaces are real now**: [anthropics/skills](https://github.com/anthropics/skills), [wshobson/agents](https://github.com/wshobson/agents), and [ClawHub](https://docs.openclaw.ai/tools/clawhub) make reusable agent capabilities browsable and installable.
2. **Workflow structure is becoming explicit**: [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) and [claude-task-master](https://github.com/eyaltoledano/claude-task-master) show how people are layering conventions, commands, and task systems on top of coding agents.
3. **Routing and agent-ops are becoming infrastructure**: [claude-code-router](https://github.com/musistudio/claude-code-router), [Claude Squad](https://github.com/smtg-ai/claude-squad), and [Repomix](https://github.com/yamadashy/repomix) highlight provider routing, multi-agent management, and codebase packaging as real operational layers.

---

## Choose a Path

<table>
  <tr>
    <td width="50%">
      <strong>🟢 New to Vibe Research</strong><br><br>
      Start: <a href="./topics/getting-started.md">Getting Started</a><br>
      Then: <a href="./topics/tools.md">Tools & Platforms</a>
    </td>
    <td width="50%">
      <strong>🔵 Developer / Builder</strong><br><br>
      Start: <a href="./topics/tools.md">Tools & Platforms</a><br>
      Then: <a href="./topics/vibe-coding.md">Vibe Coding</a> · <a href="./topics/systems.md">Systems</a> · <a href="./topics/experiment.md">Experiment</a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <strong>🔴 Researcher</strong><br><br>
      Start: <a href="./topics/surveys.md">Surveys</a><br>
      Then: <a href="./topics/ideation.md">Ideation</a> · <a href="./topics/benchmarks.md">Benchmarks</a>
    </td>
    <td width="50%">
      <strong>🟣 Creator / Operator</strong><br><br>
      Start: <a href="./topics/vibe-anything.md">Vibe Anything</a><br>
      Then: <a href="./topics/vibe-coding.md">Vibe Coding</a> · <a href="./topics/tools.md">Tools & Platforms</a>
    </td>
  </tr>
</table>

> Only have 5 minutes? Install [InnoClaw](https://github.com/SpectrAI-Initiative/InnoClaw) and try it out.

---

## Ecosystem Snapshot

<p align="center">
  <img src="files/images/claw_ecosystem.jpg" alt="CLAW Ecosystem - Vibe Research tools and platforms" width="90%">
</p>

| Layer | Representative projects | Why it matters |
|---|---|---|
| **Research copilots** | [OpenAI Deep Research](https://openai.com/index/introducing-deep-research/) · [Gemini Deep Research](https://blog.google/products/gemini/google-gemini-deep-research/) · [NotebookLM](https://notebooklm.google/) · [Prism](https://openai.com/prism/) | Fast literature synthesis, source-grounded reading, and scientific writing assistance |
| **Research systems** | [InnoClaw](https://github.com/SpectrAI-Initiative/InnoClaw) · [ResearchClaw](https://github.com/ymx10086/ResearchClaw) · [FARS](https://github.com/fars-analemma) · [AI Scientist](https://github.com/SakanaAI/AI-Scientist) · [Agent Laboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) · [EvoScientist](https://github.com/EvoScientist/EvoScientist) | End-to-end research assistance, automation, and experiment execution |
| **AI scientist platforms** | [FutureHouse Platform](https://www.futurehouse.org/research-announcements/launching-futurehouse-platform-ai-agents?_bhlid=b2b50af9254da4cf97bbad70959795fa728b14f6) · [Robin](https://www.futurehouse.org/research-announcements/demonstrating-end-to-end-scientific-discovery-with-robin-a-multi-agent-system) · [Edison Scientific](https://edisonscientific.com/) · [Kosmos](https://edisonscientific.com/articles/announcing-kosmos) | Shows the field moving from paper demos to persistent web/API platforms and validated scientific workflows |
| **Learning / self-evolving layer** | [Agent Lightning](https://github.com/microsoft/agent-lightning) · [Agent0](https://github.com/aiming-lab/Agent0) · [AgentEvolver](https://github.com/modelscope/AgentEvolver) · [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX) · [Acontext](https://github.com/memodb-io/Acontext) | Turns agent training, self-generated data, evolving workflows, and persistent skill/context memory into a real stack layer |
| **Claw ecosystem** | [OpenClaw](https://github.com/openclaw/openclaw) · [ScienceClaw](https://github.com/beita6969/ScienceClaw) · [MetaClaw](https://github.com/aiming-lab/MetaClaw) · [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | Foundation, specialization, online learning, autonomous pipelines, and the growing gateway / skill-distribution layer |
| **Execution layer** | [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview) · [Codex](https://github.com/openai/codex) · [Cursor Background Agents](https://docs.cursor.com/en/background-agent) · [GitHub Copilot Coding Agent](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent) | The coding and repo workflow layer that increasingly powers research execution |
| **Claude Code ecosystem** | [anthropics/skills](https://github.com/anthropics/skills) · [wshobson/agents](https://github.com/wshobson/agents) · [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) · [claude-code-router](https://github.com/musistudio/claude-code-router) | Shows how the Claude Code layer is expanding into skills, marketplaces, meta-frameworks, and routing infrastructure |
| **Adjacent prompt-native tools** | [v0](https://v0.dev/docs) · [Lovable](https://docs.lovable.dev/) · [Replit Agent](https://docs.replit.com/replitai/agent) | Useful for prototyping, but not the core of Vibe Research |

<table>
  <tr>
    <td width="25%" align="center"><strong><a href="./topics/tools.md">→ Tools & Platforms</a></strong></td>
    <td width="25%" align="center"><strong><a href="./topics/claw-park.md">→ Claw Park</a></strong></td>
    <td width="25%" align="center"><strong><a href="./topics/vibe-coding.md">→ Vibe Coding</a></strong></td>
    <td width="25%" align="center"><strong><a href="./topics/vibe-anything.md">→ Vibe Anything</a></strong></td>
  </tr>
</table>

---

## Plugins, Bridges & Research Connectors

A new layer is forming between "agent" and "workflow": plugin surfaces, MCP registries, skill catalogs, and chat bridges that make research agents easier to extend, discover, and operate.

| Layer | Representative resources | Why it matters |
|---|---|---|
| **Bridge & control surfaces** | [cc-connect](https://github.com/chenhg5/cc-connect) | Runs Claude Code, Cursor, Gemini CLI, Codex, and similar agents from chat surfaces such as Feishu/Lark, Slack, Telegram, and WeCom |
| **Plugin / customization layer** | [ClawHub](https://docs.openclaw.ai/tools/clawhub) · [OpenClaw Plugin Bundles](https://docs.openclaw.ai/plugins/bundles) · [awesome-claude-code-plugins](https://github.com/ccplugins/awesome-claude-code-plugins) | Shows how agent ecosystems are moving toward skill registries, plugin marketplaces, bundle compatibility, and installable capability packs |
| **Learning / memory substrate** | [Acontext](https://github.com/memodb-io/Acontext) · [anthropics/skills](https://github.com/anthropics/skills) | Shows how context, memory, and reusable skills are turning into persistent substrates for agent improvement |
| **Claude Code workflow layer** | [wshobson/agents](https://github.com/wshobson/agents) · [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) · [claude-task-master](https://github.com/eyaltoledano/claude-task-master) | Shows how commands, agent teams, skills, and task systems are turning Claude Code into a fuller development environment |
| **Routing / agent-ops layer** | [claude-code-router](https://github.com/musistudio/claude-code-router) · [Claude Squad](https://github.com/smtg-ai/claude-squad) · [Repomix](https://github.com/yamadashy/repomix) | Highlights provider routing, multi-agent session management, and codebase packaging as new operational layers around coding agents |
| **Registry / discovery layer** | [Official MCP Registry](https://modelcontextprotocol.io/registry/about) · [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) · [awesome-openclaw-skills](https://github.com/sundial-org/awesome-openclaw-skills) | Makes it easier to find, compare, and install the rapidly growing tool and skill ecosystem |
| **Research connectors** | [OpenAlex Research MCP](https://github.com/oksure/openalex-research-mcp) · [Academia MCP](https://github.com/IlyaGusev/academia_mcp) · [PapersWithCode MCP](https://github.com/hbg/mcp-paperswithcode) | Connects agents directly to literature graphs, code artifacts, datasets, and benchmark metadata |

More detailed map: [→ Tools & Platforms](./topics/tools.md)

---

## Topic Map

### Core Guides

| Topic | Description | Link |
|---|---|---|
| 🚀 **Getting Started** | 5-min demo → 30-min agent deployment → full automation | [→ Getting Started](./topics/getting-started.md) |
| 🧰 **Tools & Platforms** | Core platforms, literature tools, writing aids, experiment tools | [→ Tools & Platforms](./topics/tools.md) |
| 🦞 **Claw Park** | Ecosystem map for what each Claw project is building and where it fits | [→ Claw Park](./topics/claw-park.md) |
| 💻 **Vibe Coding** | Terminal agents, coding agents, background agents, and repo guardrails | [→ Vibe Coding](./topics/vibe-coding.md) |
| 🎨 **Vibe Anything** | Adjacent prompt-native workflows for apps, design, writing, slides, and ops | [→ Vibe Anything](./topics/vibe-anything.md) |

### Research Topics (35+ papers)

| Topic | Core Question | Papers | Link |
|---|---|---|---|
| 📄 **Surveys** | Landscape & evolution of the field | 5 | [→ Surveys](./topics/surveys.md) |
| ⚙️ **Systems** | How to design end-to-end research systems | 6 | [→ Systems](./topics/systems.md) |
| 💡 **Ideation** | Can LLMs generate novel ideas | 6 | [→ Ideation](./topics/ideation.md) |
| 📚 **Synthesis** | How to synthesize literature at scale | 5 | [→ Synthesis](./topics/synthesis.md) |
| 🧪 **Experiment** | How agents automate experiments | 4 | [→ Experiment](./topics/experiment.md) |
| ✍️ **Writing & Review** | LLM-assisted writing & peer review | 4 | [→ Writing & Review](./topics/writing-review.md) |
| 📊 **Benchmarks** | How to evaluate research agents | 5 | [→ Benchmarks](./topics/benchmarks.md) |

---

## Reading Modes

<table>
  <tr>
    <td width="33%">
      <strong>Read The Field</strong><br><br>
      <a href="./topics/surveys.md">Surveys</a> · <a href="./topics/systems.md">Systems</a> · <a href="./topics/benchmarks.md">Benchmarks</a>
    </td>
    <td width="33%">
      <strong>Build The Stack</strong><br><br>
      <a href="./topics/tools.md">Tools & Platforms</a> · <a href="./topics/claw-park.md">Claw Park</a> · <a href="./topics/vibe-coding.md">Vibe Coding</a>
    </td>
    <td width="33%">
      <strong>Prototype Beyond Research</strong><br><br>
      <a href="./topics/vibe-anything.md">Vibe Anything</a>
    </td>
  </tr>
</table>

---

## Useful Resources

**Introductions**: [AI for Science (Nature)](https://www.nature.com/articles/s41586-023-06221-2) · [LLM Agents (Lilian Weng)](https://lilianweng.github.io/posts/2023-06-23-agent/) · [Agentic Patterns (Andrew Ng)](https://www.deeplearning.ai/the-batch/how-agents-can-improve-llm-performance/)

**Awesome Lists**: [LLM Agent Survey](https://github.com/Paitesanshi/LLM-Agent-Survey) · [AI Agents](https://github.com/e2b-dev/awesome-ai-agents) · [Scientific Idea Generation](https://github.com/wjie0309/awesome-scientific-idea-generation)

**Search & Reading**: [Semantic Scholar](https://www.semanticscholar.org/) · [Elicit](https://elicit.com/) · [Consensus](https://consensus.app/) · [Connected Papers](https://www.connectedpapers.com/)

**AI Scientist Platforms**: [FutureHouse Platform](https://www.futurehouse.org/research-announcements/launching-futurehouse-platform-ai-agents?_bhlid=b2b50af9254da4cf97bbad70959795fa728b14f6) · [Robin](https://www.futurehouse.org/research-announcements/demonstrating-end-to-end-scientific-discovery-with-robin-a-multi-agent-system) · [Edison Scientific](https://edisonscientific.com/) · [Kosmos](https://edisonscientific.com/articles/announcing-kosmos)

**Learning / Self-Evolving Agents**: [Agent Lightning](https://github.com/microsoft/agent-lightning) · [Agent0](https://github.com/aiming-lab/Agent0) · [AgentEvolver](https://github.com/modelscope/AgentEvolver) · [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX) · [Acontext](https://github.com/memodb-io/Acontext) · [Awesome-Self-Evolving-Agents](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents)

**Execution**: [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview) · [Codex](https://github.com/openai/codex) · [Cursor Background Agents](https://docs.cursor.com/en/background-agent) · [GitHub Copilot Coding Agent](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent) · [Gemini CLI](https://github.com/google-gemini/gemini-cli)

**Claude Code Ecosystem**: [anthropics/skills](https://github.com/anthropics/skills) · [wshobson/agents](https://github.com/wshobson/agents) · [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) · [claude-code-router](https://github.com/musistudio/claude-code-router) · [Claude Squad](https://github.com/smtg-ai/claude-squad) · [claude-task-master](https://github.com/eyaltoledano/claude-task-master) · [Repomix](https://github.com/yamadashy/repomix)

**Prototyping**: [v0](https://v0.dev/docs) · [Lovable](https://docs.lovable.dev/) · [Replit Agent](https://docs.replit.com/replitai/agent) · [Figma AI](https://www.figma.com/ai/) · [Canva AI](https://www.canva.com/canva-ai/)

**Conferences**: NeurIPS · ICML · ICLR · ACL · AAAI · EMNLP

---

## Contribute

Submit resources via [Resource Suggestion](https://github.com/SpectrAI-Initiative/Vibe-Research-Guide/issues/new?template=resource_suggestion.yml) · Contribute via PR · Follow the [curation guidelines](docs/curation-guidelines.md)

<a href="https://github.com/SpectrAI-Initiative/Vibe-Research-Guide/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=SpectrAI-Initiative/Vibe-Research-Guide" />
</a>

---

<details>
<summary><b>Citation</b></summary>

```
@misc{viberesearch2026,
  title = {Vibe Research Guide},
  author = {Aaron Wang and Contributors},
  year = {2026},
  url = {https://github.com/SpectrAI-Initiative/Vibe-Research-Guide},
}
```

</details>

<details>
<summary><b>Changelog</b></summary>

- **2026-W16**: Added a dedicated learning / RL / self-evolving layer to the guide, including Agent Lightning, Agent0, AgentEvolver, EvoAgentX, Acontext, and Awesome-Self-Evolving-Agents
- **2026-W14**: Added 2026 Q1 signals for OpenClaw platformization, FutureHouse / Robin / BixBench, and Edison Scientific / Kosmos; refreshed ecosystem framing across the guide
- **2026-W14**: Added recent Claude Code ecosystem signals, including anthropics/skills, wshobson/agents, SuperClaude, claude-code-router, Claude Squad, claude-task-master, and Repomix
- **2026-W13**: Added a new plugin / bridge / registry layer to the guide, including cc-connect, OpenAlex Research MCP, Academia MCP, PapersWithCode MCP, and more Claw ecosystem positioning
- **2026-W13**: Added core tools & platforms (InnoClaw, ResearchClaw, FARS, Orchestra, OpenClaw, EvoScientist); added Deep Research tools, OpenAI Prism, MCP Servers; switched all content to English; expanded to 35+ papers across 9 topic files
- **2026-W12**: Redesigned README into a stronger landing page with cleaner hierarchy, card-style path selection, and a more visual ecosystem map
- **2026-W12**: Hub-and-spoke architecture reorganization
- **2026-W12**: Initial public release

Full history: [`CHANGELOG.md`](CHANGELOG.md)

</details>

MIT License · [![Star History Chart](https://api.star-history.com/svg?repos=SpectrAI-Initiative/Vibe-Research-Guide&type=Date)](https://star-history.com/#SpectrAI-Initiative/Vibe-Research-Guide&Date)
