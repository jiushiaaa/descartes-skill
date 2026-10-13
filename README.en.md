# René Descartes · Skill

[中文](README.md) | **English**

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with Nuwa](https://img.shields.io/badge/Made_with-Nuwa-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

Doubt, judgment, and grounds of knowledge. A bounded, source-linked thinking resource with neutral analysis by default and an explicitly enabled expression mode.

Built using [Nuwa by Huashu](https://github.com/alchaincyf/nuwa-skill), with primary-source research and independent model evaluation.

[Usage](USAGE.md) · [Research and entry point](SKILL.md) · [Evaluation](FIDELITY.md)

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

## Use

Ask: “Use René Descartes's ideas to analyze this problem, separating source claims from contemporary inference.” For expression simulation, explicitly request expression mode. Fiction writing and review use ideas without taking over the narrative voice. See the bilingual [usage guide](USAGE.md).

## Coverage and evidence

The [entry point](SKILL.md) routes to documented, bounded methods and [extraction notes](EXTRACTION.md). The research directory records sources, actual reading ranges, translations, and unresolved gaps. It is not a distillation of the complete works. Research notes remain in their original languages.

## Evaluation snapshot

R3 independent scores: **90/100** and **88/100**. Both reviewers at A with no unresolved blocker: **yes**. [Full record](FIDELITY.md).

This release preserves the user-accepted snapshot; score optimization has stopped. Scores are model evaluations of the frozen Chinese runtime files, not academic certification or a new evaluation of this release packaging. The initial anonymous test omitted the question wording; this limitation and subsequent checks are retained. Some expression or reasoning weaknesses remain.

## Related skills

[Independent repository](https://github.com/jiushiaaa/descartes-skill) · [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills) — 21 original and 25 attributed upstream modules, kept independent.

## Acknowledgments and license

Thanks to Huashu / alchaincyf, Nuwa, the Agent Skills contributors, and the primary-source editors listed in the research notes. See [attribution](ATTRIBUTION.md). Project-original material is [MIT licensed](LICENSE); third-party source quotations retain their rights. README and usage documentation are bilingual; research notes are not represented as fully translated.
