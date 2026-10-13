# 笛卡尔 · Skill

**中文** | [English](README.en.md)

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with Nuwa](https://img.shields.io/badge/Made_with-Nuwa-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

怀疑、判断与认识根据。以可追溯原作和明确边界支持思想分析，默认中性，人物表达单独开启。

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

[使用说明](USAGE.md) · [思想入口与研究材料](SKILL.md)

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/descartes-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `descartes-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/descartes-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用

例如：“用笛卡尔的思想分析这个问题，区分原作观点与当代推断。”需要表达模拟时明确开启人物表达模式；文游创作或审读只取思想，不接管作品口吻。详见[双语使用说明](USAGE.md)。

## 思想方法

- 知识主张的根据
- 复杂论证的次序
- 确定性不足却必须行动
- 心身解释的范畴混用

详见 [SKILL.md](SKILL.md) 与 [EXTRACTION.md](EXTRACTION.md)。目录中的候选、局部证据和未读范围均保留，不能把它们理解成全集蒸馏完成。

## 许可

项目原创材料采用 [MIT](LICENSE)，引用的原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
