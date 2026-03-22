<h1 align="center">Vibe Research Guide<br>Vibe Anything</h1>

> This page is intentionally outside the core Vibe Research track. The same agentic pattern now appears in product prototyping, design, writing, slides, data work, and operations. That is useful, but it should be separated from scientific research so the main guide stays rigorous.

## What is Vibe Anything

Vibe Anything is the broader habit of using AI agents or prompt-native tools to move from intent to artifact quickly:

- prompt → app
- prompt → design
- prompt → report
- prompt → deck
- prompt → workflow

The upside is speed. The downside is that quality can look finished before it is actually correct, maintainable, or useful.

---

## Common Arenas

| Arena | Typical tools | What works well | What still needs human judgment |
|---|---|---|---|
| App prototyping | [v0](https://v0.dev/docs), [Lovable](https://docs.lovable.dev/), [Replit Agent](https://docs.replit.com/replitai/agent) | Landing pages, CRUD apps, internal tools, demos | Architecture, auth, security, long-term maintainability |
| Design exploration | [Figma AI](https://www.figma.com/ai/) | Moodboards, wireframes, fast interface variations | Product taste, usability, brand coherence |
| Knowledge work | [NotebookLM](https://notebooklm.google/), [Notion AI](https://www.notion.com/product/ai) | Source-grounded notes, synthesis, brief generation | Claim verification, prioritization, final judgment |
| Slides and content | [Canva AI](https://www.canva.com/canva-ai/) | Draft decks, summaries, visuals, and creative assets | Narrative quality, factual precision, audience fit |
| Automation / ops | [Gemini CLI](https://github.com/google-gemini/gemini-cli), [OpenHands](https://github.com/All-Hands-AI/OpenHands) | Scripts, glue code, repetitive internal workflows | Access control, irreversible actions, production safety |

---

## When It Actually Works

Vibe Anything usually works best when:

1. The task is **compressible** into a visible artifact quickly.
2. A rough first draft is already valuable.
3. The human reviewer can spot bad outputs fast.
4. The cost of redoing the output is low.

It works much worse when:

1. Failure is silent instead of obvious.
2. The domain has hidden constraints.
3. Long-term maintainability matters more than speed.
4. You confuse a polished draft with a validated solution.

---

## Workflow Patterns

### 1. Prototype Fast, Normalize Early

Use prompt-native builders for the first draft, then move into normal engineering or design workflows as soon as the direction is worth keeping.

### 2. Keep One Source of Truth

Generated artifacts should eventually resolve back to Git, Figma files, docs, tickets, or other durable systems of record.

### 3. Review for Domain Risk, Not Surface Polish

The right question is rarely "does it look good?" It is usually:

- Is it true?
- Is it usable?
- Is it secure?
- Can the team maintain it?

---

## Evaluation Checklist

| Question | Why it matters |
|---|---|
| Is the output grounded in real sources or constraints? | AI can sound finished before it is correct |
| Can another person maintain or reproduce it? | One-shot outputs often hide fragility |
| Did the tool save meaningful time after cleanup? | Some "fast" workflows only shift labor downstream |
| Would you trust it in a production or public setting? | Prototype quality is not deployment quality |

---

## Relationship to Vibe Research

Vibe Research asks: can AI help generate valid scientific knowledge?

Vibe Anything asks: can AI help me produce a useful artifact quickly?

Those are related, but not interchangeable. Research needs stronger grounding, evaluation, reproducibility, and skepticism.

---

## Suggested Path

1. If your real goal is science, go back to [Getting Started](./getting-started.md) or [Tools & Platforms](./tools.md).
2. If your goal is software execution, continue with [Vibe Coding](./vibe-coding.md).
3. If your goal is a draft, prototype, or workflow artifact, this page is the right abstraction layer.

---

> **Home**: [README](../README.md) · **Prev**: [Vibe Coding](./vibe-coding.md)
