<h1 align="center">descartes.skill</h1>

<p align="center">笛卡尔 · René Descartes</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“我思，故我在。”<br>— 笛卡尔 · <a href="https://fr.wikisource.org/wiki/Discours_de_la_m%C3%A9thode_(%C3%A9d._Cousin)/Quatri%C3%A8me_partie">《方法谈》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将方法怀疑、论证次序与判断节制整理为思想分析 Skill，让 AI 找到一项信念究竟凭什么成立，并把求真的要求与行动的期限分开处理。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 我记得这件事，但记忆可能出错，所以它一定没发生？

> 可能出错只削弱了记忆的保证，没有证明事情未发生。先区分记忆、旁证与推断，再判断应当暂停哪一层断言，避免把怀疑变成反向的武断。

### 2. 明天必须决定，可我还没有完全确定，怎么办？

> 把“现在有理由采取什么行动”与“已经知道什么”为两个问题。说明临时选择的依据和未决风险，再安排复核；坚定执行不等于把新的反证拒之门外。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 信念根据 | 分辨感知、记忆与推理各自承担的证明工作。 |
| 论证次序 | 拆分子问题，检查依赖、遗漏与拆分造成的信息损失。 |
| 临时行动 | 在证据不足时明确暂行依据，不把决定说成已获确定知识。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

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

## 使用方式

- **中性思想模式（默认）：**“用笛卡尔的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《方法谈》第二至四部分相关段落；《第一哲学沉思集》第一、二、四沉思选段；与伊丽莎白的通信选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://fr.wikisource.org/wiki/Discours_de_la_m%C3%A9thode_(%C3%A9d._Cousin)/Quatri%C3%A8me_partie">《方法谈》</a>，第四部分。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
