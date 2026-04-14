<h1 align="center">Vibe Research Guide<br>Vibe Coding</h1>

> Vibe Coding is not the same thing as Vibe Research, but it is now a core execution layer for research automation. If a research agent cannot inspect repos, edit code safely, run experiments, debug failures, and hand back reviewable diffs, it usually cannot close the loop from idea to result.

## What is Vibe Coding

Vibe Coding means using AI agents as active collaborators in software creation: reading a codebase, proposing plans, editing files, running commands, opening PRs, and iterating with human supervision.

For research workflows, this matters because modern Vibe Research increasingly depends on:

1. **Experiment automation**: writing and fixing training / evaluation scripts
2. **Repo operations**: understanding existing code instead of generating toy snippets
3. **Async execution**: letting agents handle long-running engineering work while the researcher keeps moving

---

## 2026 Tool Landscape

| Tool | Mode | Why it matters | Best for |
|---|---|---|---|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview) | Terminal coding agent | Strong repository workflows, approvals, and MCP support | Engineers working directly in real repos |
| [Codex](https://github.com/openai/codex) | Local + cloud coding agent | Lets you run tasks locally or delegate background software work | Async task queues, engineering support |
| [Cursor Background Agents](https://docs.cursor.com/en/background-agent) | Remote async agent | Parallelizes longer tasks without blocking local flow | Delegation-heavy engineering teams |
| [GitHub Copilot Coding Agent](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent) | Issue-to-PR GitHub agent | Works inside GitHub review and issue workflows | Teams that want agent work to stay in GitHub |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Open-source terminal agent | Strong for CLI-native workflows with search grounding | Builders who want an open CLI agent |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | Open-source full-stack agent platform | Useful when you want infra for sandboxed execution and agent orchestration | Teams building their own coding-agent stack |
| [v0](https://v0.dev/docs) | Prompt-to-app builder | Very fast UI and frontend prototyping with code output | Starting from zero to a demo |
| [Lovable](https://docs.lovable.dev/) | Product-builder agent | Good for fast full-stack MVP generation with GitHub sync | Founder-style product experiments |

---

## Claude Code Ecosystem Signals

Claude Code is increasingly less like one terminal binary and more like the center of a wider execution ecosystem:

| Project | Link | Why it matters |
|---|---|---|
| **anthropics/skills** | [GitHub](https://github.com/anthropics/skills) | Official public Agent Skills repo and marketplace-style source for reusable Claude Code capabilities |
| **wshobson/agents** | [GitHub](https://github.com/wshobson/agents) | Large community marketplace for Claude Code agents, commands, hooks, and skills |
| **SuperClaude Framework** | [GitHub](https://github.com/SuperClaude-Org/SuperClaude_Framework) | Opinionated meta-framework that layers personas, commands, and workflow structure onto Claude Code |
| **claude-code-router** | [GitHub](https://github.com/musistudio/claude-code-router) | Adds provider routing, request transformation, and workflow infrastructure around Claude Code |
| **Claude Squad** | [GitHub](https://github.com/smtg-ai/claude-squad) | Focuses on multi-agent terminal workflows with isolated workspaces and team-style management |
| **claude-task-master** | [GitHub](https://github.com/eyaltoledano/claude-task-master) | Turns agent execution into a more explicit task-management and checkpoint workflow |
| **Repomix** | [GitHub](https://github.com/yamadashy/repomix) | Useful for packaging and compressing codebase context so coding agents can ingest repos more effectively |

The practical takeaway: if you are evaluating the execution layer for Vibe Research, look at the surrounding ecosystem, not just the core binary.

---

## Execution Layer vs Learning Layer

This distinction matters more now than it did a year ago:

| Layer | Representative projects | What it actually improves |
|---|---|---|
| **Execution layer** | [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview) · [Codex](https://github.com/openai/codex) · [Cursor Background Agents](https://docs.cursor.com/en/background-agent) · [claude-task-master](https://github.com/eyaltoledano/claude-task-master) · [Repomix](https://github.com/yamadashy/repomix) | Repo work, task execution, code edits, reviews, and async engineering throughput |
| **Learning / optimization layer** | [Agent Lightning](https://github.com/microsoft/agent-lightning) · [Agent0](https://github.com/aiming-lab/Agent0) · [AgentEvolver](https://github.com/modelscope/AgentEvolver) · [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX) · [Acontext](https://github.com/memodb-io/Acontext) | Policy improvement, self-generated training signal, evolving workflows, and persistent reusable memory |

The practical rule: Vibe Coding tells you whether an agent can do the work now; the learning layer tells you whether the agent can get better over repeated use.

---

## Working Modes

| Mode | Typical tools | When to use it | Failure mode |
|---|---|---|---|
| Terminal pair-programming | Claude Code, Gemini CLI | You need tight supervision and repo awareness | Human becomes a copy-paste bottleneck |
| Async background execution | Codex, Cursor Background Agents | The task is bounded and can run in parallel | Agents drift without checkpoints |
| GitHub-native delegation | GitHub Copilot Coding Agent | Work already lives in issues / PRs | Too much context stays off-repo |
| Prompt-to-product generation | v0, Lovable, Replit Agent | You need a prototype before you need an architecture | Generated code may not be production-ready |

---

## Recommended Workflows

### 1. Repo-Native Engineering

Best when the codebase already exists.

1. Ask the agent to inspect the repo and restate the task.
2. Make it propose a short plan before editing.
3. Require changes on a branch, not on `main`.
4. Review diff, tests, and assumptions before merge.

### 2. Research Experiment Loop

Best when you are iterating on papers, baselines, or evals.

1. Use a research copilot to refine the experiment question.
2. Hand the implementation to a coding agent.
3. Run the smallest reproducible experiment first.
4. Capture metrics, failure cases, and environment details in the repo.

### 3. Prompt-to-App Handoff

Best when you need a fast demo.

1. Prototype the UI or flow in v0 / Lovable.
2. Move the useful output into a normal repo quickly.
3. Use a repo-native coding agent for cleanup, tests, auth, and deployment hardening.

---

## Guardrails

1. **Branch first**: agent-heavy workflows should not edit `main` directly.
2. **Keep instructions in-repo**: `AGENTS.md`, `CLAUDE.md`, or `GEMINI.md` reduce repeated prompting.
3. **Prefer diffs over dumps**: ask for reviewable patches, not giant regenerated files.
4. **Run narrow tests first**: smoke tests and linting catch many agent regressions cheaply.
5. **Preserve source of truth**: prompts are not documentation; the repo is.
6. **Escalate gradually**: start with low-risk edits before giving agents deployment or production access.

---

## How Vibe Coding Connects Back to Vibe Research

| Research stage | Why coding agents matter |
|---|---|
| Literature synthesis | Build scrapers, parsers, retrieval tools, and note pipelines |
| Ideation | Turn speculative ideas into benchmarkable prototypes |
| Experiment execution | Write, run, debug, and compare experiment variants |
| Writing & review | Reproduce tables, regenerate figures, and package artifacts |
| Benchmarking | Maintain eval harnesses, task suites, and reproducibility scripts |

---

## Reading / Tooling Trail

1. Start with [Tools & Platforms](./tools.md) for the research-specific stack.
2. Pair this page with [Experiment](./experiment.md) and [Systems](./systems.md).
3. If your task is not really research, move to [Vibe Anything](./vibe-anything.md) and keep the scope honest.

---

> **Home**: [README](../README.md) · **Prev**: [Tools & Platforms](./tools.md) · **Next**: [Vibe Anything](./vibe-anything.md)
