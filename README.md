# Harness Engineering, Dissected

A study guide to how coding agents are built: what sits around the model, how the main open and commercial agents differ, and what later research measured about those designs.

**Read it here:** https://acgh.github.io/harness-engineering-dissected/

## What it covers

The guide is built on one paper:

> P. Barbaste, T. Darrigol, G. Vu, T. Wiltberger. *Harness Engineering: Anatomy, Architecture, and Evolution of Coding Agents. A Source-Code Study of Eleven Systems.* arXiv:2609.00006, July 2026. https://arxiv.org/abs/2609.00006

The paper reads the source code of eleven coding agents, including Claude Code, Codex CLI, Gemini CLI, OpenHands, Aider and OpenCode. It describes the seven subsystems every agent harness has: the agent loop, LLM integration, tools, memory and context, safety, orchestration and extensibility.

The guide adds findings from 49 related papers by other groups, published between September 2025 and November 2026. They benchmarked, attacked or tried to improve these designs. Each finding links to its paper.

## How it's organised

- **Quick track** (about 25 minutes): for engineers starting their first harness. The core idea, ten design decisions, a 90-line starter harness, and what later research changed.
- **Deep track** (about 2 hours for a first pass): for engineers who have already built one. Every subsystem in detail, the paper's 18 recommendations with a verdict from later research on each, nine further recommendations, and an explorer for all 49 papers.

Each section ends with a checkpoint, so you can read it over several sittings and pick up where you left off.

## Notes on accuracy

- Benchmark scores and system details come from the papers cited and were current as of their publication. Agent versions change weekly; check the source before relying on a specific number.
- Where the source paper contains an error, the guide corrects it and says so. For example, the AHE result is 69.7% to 77.0% on Terminal-Bench 2, not 71.9% on SWE-bench Verified.
- This is an independent summary. It isn't affiliated with or reviewed by the authors of any paper it covers.

## Privacy

The page is a single HTML file with its fonts built in. It makes no network requests apart from links you click, and it has no analytics or tracking. Reading progress is stored only in your own browser's local storage.

## License

Text and figures: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Starter code: [MIT](https://opensource.org/licenses/MIT).

The summarised papers remain the work of their authors, under their own licenses.
