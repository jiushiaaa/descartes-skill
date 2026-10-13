# René Descartes · Skill

[中文](README.md) | **English**

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with Nuwa](https://img.shields.io/badge/Made_with-Nuwa-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

Doubt, judgment, and grounds of knowledge. A bounded, source-linked thinking resource with neutral analysis by default and an explicitly enabled expression mode.

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

[Usage](USAGE.md) · [Research and entry point](SKILL.md)

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

## License

Project-original material is [MIT licensed](LICENSE). Source quotations retain their separate rights. See [attribution](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
