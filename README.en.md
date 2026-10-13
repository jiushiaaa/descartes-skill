<h1 align="center">descartes.skill</h1>

<p align="center">笛卡尔 · René Descartes</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“I think, therefore I am.”<br>— René Descartes · <a href="https://fr.wikisource.org/wiki/Discours_de_la_m%C3%A9thode_(%C3%A9d._Cousin)/Quatri%C3%A8me_partie">Discourse on the Method</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for methodical doubt, ordered reasoning, and disciplined judgment: identify what supports a belief and distinguish the demands of inquiry from the deadlines of action.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Memory can be mistaken. Does that prove the event I remember never happened?

> Fallibility weakens the guarantee supplied by memory; it does not prove the event did not occur. Separate recollection, corroboration, and inference before deciding which claim to suspend.

### 2. I must decide tomorrow, but I am not certain. What can I do?

> Separate what action is presently justified from what is known. State the provisional grounds and unresolved risks, then specify what would prompt review. Resolve does not require ignoring new evidence.

## What is distilled

| Method | What it helps examine |
|---|---|
| Grounds of belief | Separate the roles of perception, memory, and inference. |
| Order of reasoning | Check dependencies, omissions, and what decomposition leaves out. |
| Provisional action | State grounds for acting without presenting a decision as certain knowledge. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/descartes-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `descartes-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/descartes-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use René Descartes’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Relevant passages in parts II–IV of the Discourse; selections from Meditations I, II, and IV; selected correspondence with Elisabeth.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://fr.wikisource.org/wiki/Discours_de_la_m%C3%A9thode_(%C3%A9d._Cousin)/Quatri%C3%A8me_partie">Discourse on the Method</a>, part IV. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
