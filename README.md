> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/threads-growth-manager)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/threads-growth-manager/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# 🧵 threads-growth-manager

**Grow on Meta Threads with conversation-starting posts, reply strategy and a content bank. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/threads-growth-manager)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/threads-growth-manager?style=social)](https://github.com/milad-ahmd/threads-growth-manager)
![Category](https://img.shields.io/badge/category-Social%20Platforms-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/threads-growth-manager/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- threads-growth-manager
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/threads-growth-manager /tmp/threads-growth-manager
mkdir -p ~/.claude/skills && cp -r /tmp/threads-growth-manager/skills/threads-growth-manager ~/.claude/skills/
```

**Per project:** copy `skills/threads-growth-manager` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/threads-growth-manager/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Write 20 Threads posts for my brand
How do I grow on Threads?
```

The full workflow, rules and output format are in [`SKILL.md`](skills/threads-growth-manager/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
