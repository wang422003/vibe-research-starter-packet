<h1 align="center">Vibe Research Guide<br>Claw Park</h1>

> Claw Park is the ecosystem map for the growing Claw family. The goal is simple: when a new Claw project appears, you should be able to answer two questions quickly: what is it trying to do, and where does it fit in the stack?

## Why Claw Park Exists

The Claw ecosystem is no longer one product. It now spans:

1. **Foundation frameworks**
2. **Research workspaces**
3. **Personal research copilots**
4. **Self-evolving agent layers**
5. **Fully autonomous research pipelines**

Without a map, the names blur together. Claw Park keeps them separated by job, not by branding.

---

## Ecosystem Map

| Project | What it is doing | Role in the stack | Best for |
|---|---|---|---|
| [OpenClaw](https://github.com/openclaw/openclaw) | General-purpose personal AI assistant evolving into a gateway, control UI, skill registry, and compatible bundle platform | Foundation platform | Builders who want a base platform, distribution layer, and reusable skills |
| [InnoClaw](https://github.com/SpectrAI-Initiative/InnoClaw) | Self-hostable research workspace for grounded chat, paper study, scientific skills, and research execution | Research workspace | Labs and self-hosters who want files, papers, and execution in one place |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) | Personal research assistant for literature review, note-taking, experiment tracking, and paper writing | Personal research copilot | Individual researchers who want an end-to-end daily driver |
| [ScienceClaw](https://github.com/beita6969/ScienceClaw) | Self-evolving AI research colleague with many skills, persistent memory, and research focus | Scientific specialist | Research-heavy users who want a stronger scientific agent |
| [ScienceClaw (alt repo)](https://github.com/Zaoqu-Liu/ScienceClaw) | "AI research lab that never sleeps" with multi-agent coverage and broad data / database access | Research-lab variant | Users who want an ambitious lab-style automation stack |
| [MetaClaw](https://github.com/aiming-lab/MetaClaw) | Learning framework that turns real conversations into reusable skills and online evolution | Evolution engine | Builders interested in adaptive agents and in-the-wild learning |
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | Fully autonomous idea-to-paper pipeline with experiments, review, verification, and final deliverables | Autonomous pipeline | People testing how far autonomous research generation can go |
| [ResearchClaw Desktop App](https://noietch.github.io/ResearchClaw/) | Local-first desktop app for PDF chat, note-taking, and paper reading workflows | Reading / note-taking surface | Readers who want a lighter-weight research desktop |

---

## A Practical Mental Model

Think about the ecosystem as layers instead of sibling products:

| Layer | Main question | Representative Claw |
|---|---|---|
| Base platform | What gateway, assistant substrate, and skill-distribution layer do I build on? | OpenClaw |
| Workspace | Where do I chat over files, papers, and tasks? | InnoClaw |
| Daily copilot | What helps me read, track, and write every day? | ResearchClaw |
| Specialist scientist | What pushes deeper into scientific assistance and memory? | ScienceClaw |
| Evolution layer | What helps the agent learn from use over time? | MetaClaw |
| Autonomous pipeline | What tries to do the full research loop for me? | AutoResearchClaw |

This avoids a common mistake: comparing all Claws as if they were trying to solve the exact same problem.

---

## Where Research Claws Are Diverging

The interesting shift is not just "more Claws." It is that research-oriented Claws are now splitting into clearly different bets:

| Pattern | Representative projects | What the bet is |
|---|---|---|
| Grounded research workspace | InnoClaw · ResearchClaw Desktop App | Researchers want file-aware, paper-aware, local-first workspaces instead of generic chat |
| Daily research copilot | ResearchClaw | The core value is steady literature, notes, tracking, and writing support rather than maximum autonomy |
| Scientific specialist | ScienceClaw | The agent should behave more like a persistent scientific collaborator with deeper research memory |
| Learning / evolution engine | MetaClaw | The long-term moat is online learning, skill extraction, and adaptation from real use |
| Full autonomy pipeline | AutoResearchClaw | The system should run as much of the idea-to-paper loop as possible with minimal intervention |
| Skill ecosystem and discovery | OpenClaw · awesome-openclaw-skills | Ecosystem value now depends on reusable skills, distribution, and community discovery, not only the base agent |

This is why "Which Claw is best?" is often the wrong question. The better question is which layer of the research stack you are trying to strengthen.

---

## Beyond Claw: The Wider Learning Layer

MetaClaw is the clearest Claw-native representative of the learning layer, but the surrounding ecosystem is now broader than Claw itself.

| Outside the Claw family | What it contributes |
|---|---|
| [Agent Lightning](https://github.com/microsoft/agent-lightning) | General agent training with RL, automatic prompt optimization, and SFT |
| [Agent0](https://github.com/aiming-lab/Agent0) · [AgentEvolver](https://github.com/modelscope/AgentEvolver) | Self-generated evolution loops, zero-data improvement, and agent learning from its own exploration |
| [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX) · [EvoScientist](https://github.com/EvoScientist/EvoScientist) | Workflow-level evolution and scientist-loop optimization |
| [Acontext](https://github.com/memodb-io/Acontext) | Persistent context, memory, and reusable skills as part of agent improvement |

The useful mental model is: MetaClaw shows how learning can live inside the Claw ecosystem, while the wider self-evolving-agent space shows that this is becoming a separate stack layer across the whole agent field.

---

## Skills, Marketplaces, And Remote Control

The broader ecosystem is no longer only project repos. It now includes a distribution and control layer around those repos:

| Layer | Example | Why it matters |
|---|---|---|
| Skill marketplace | [ClawHub](https://docs.openclaw.ai/tools/clawhub) | Makes OpenClaw look more like a living ecosystem with browsable skills and reusable tool surfaces |
| Compatible bundles | [OpenClaw Plugin Bundles](https://docs.openclaw.ai/plugins/bundles) | Suggests agent ecosystems may interoperate through installable bundle compatibility, not only isolated plugins |
| Skill discovery | [awesome-openclaw-skills](https://github.com/sundial-org/awesome-openclaw-skills) | Makes OpenClaw-style skills easier to browse, compare, and reuse |
| Chat control surface | [cc-connect](https://github.com/chenhg5/cc-connect) | Lets teams operate terminal agents from messaging tools instead of requiring everyone to sit inside a shell |
| Plugin discovery | [awesome-claude-code-plugins](https://github.com/ccplugins/awesome-claude-code-plugins) | Shows how coding-agent ecosystems are becoming layered and extensible |
| Tool registry | [Official MCP Registry](https://modelcontextprotocol.io/registry/about) · [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Standardizes discovery and installation of external tools that research agents depend on |

This is not "another Claw," but it changes how Claws spread: through skills, registries, and remote-control surfaces rather than only through monolithic apps.

---

## Why OpenClaw Matters Right Now

The main reason OpenClaw matters in 2026 Spring is not just popularity. It is that the product now points toward a broader platform shape:

1. **Gateway**: it can sit between users, chat surfaces, models, and tools.
2. **Control layer**: it is growing a clearer dashboard / operations surface instead of only a chat shell.
3. **Marketplace layer**: [ClawHub](https://docs.openclaw.ai/tools/clawhub) turns skills into a browsable public layer.
4. **Compatibility layer**: [Plugin Bundles](https://docs.openclaw.ai/plugins/bundles) hint at cross-ecosystem portability instead of hard ecosystem silos.

That makes OpenClaw more important as infrastructure than as just one more assistant app.

---

## Project Notes

### OpenClaw

OpenClaw is the broad platform play. It is no longer best understood as only a general assistant shell. The stronger reading now is: gateway plus control surface plus skill registry plus compatible-bundle layer. When another Claw project says it is "compatible with OpenClaw" or builds on the Claw ecosystem, this is increasingly the infrastructure stack they mean, not only a frontend.

### InnoClaw

InnoClaw is the workspace play. Its strength is turning a folder-backed environment into a grounded research workspace for paper study, file-aware chat, and research execution. It is the most natural choice when you want researchers to stay close to their actual files and papers.

### ResearchClaw

ResearchClaw is the day-to-day research copilot. It is positioned around practical research operations: literature review, note-taking, experiment tracking, and writing. Compared with more autonomous systems, it reads as a tool you live with rather than a pipeline you launch and wait for.

### ScienceClaw

ScienceClaw is the research specialist. The strongest signal in its positioning is self-evolution plus scientific focus. If OpenClaw is broad and ResearchClaw is practical, ScienceClaw is where the ecosystem leans harder into the "scientific colleague" idea.

### MetaClaw

MetaClaw is the learning layer. It matters because it is not mainly another frontend or another paper workflow. Its core claim is that agents should learn from real conversations, extract reusable skills, and improve online over time.

### AutoResearchClaw

AutoResearchClaw is the autonomy bet. It is the clearest "chat an idea, get a paper" pipeline in the ecosystem: literature, experiment code, review, verification, and deliverables. It is the right reference if you want to study maximum automation, not minimum-risk daily use.

---

## Which Claw Should You Start With

| If you want... | Start here |
|---|---|
| A broad assistant foundation | OpenClaw |
| A grounded research workspace | InnoClaw |
| A practical personal research assistant | ResearchClaw |
| A more research-specialized evolving scientist | ScienceClaw |
| Learning and evolution infrastructure | MetaClaw |
| Full idea-to-paper autonomy | AutoResearchClaw |

---

## Reading Trail

1. Read [Tools & Platforms](./tools.md) for the broader research tool stack.
2. Read [Systems](./systems.md) if you care about end-to-end autonomous research.
3. Read [Vibe Coding](./vibe-coding.md) if your next question is how these systems actually execute code and repo work.

---

> **Home**: [README](../README.md) · **Prev**: [Tools & Platforms](./tools.md) · **Next**: [Vibe Coding](./vibe-coding.md)
