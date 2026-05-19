# Careful Coding Skill

[![skills.sh](https://skills.sh/b/tuoitho/careful-coding-skill)](https://skills.sh/tuoitho/careful-coding-skill)
[![GitHub stars](https://img.shields.io/github/stars/tuoitho/careful-coding-skill?style=social)](https://github.com/tuoitho/careful-coding-skill/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/tuoitho/careful-coding-skill)](https://github.com/tuoitho/careful-coding-skill/commits/main)
[![Repo size](https://img.shields.io/github/repo-size/tuoitho/careful-coding-skill)](https://github.com/tuoitho/careful-coding-skill)

A practical agent skill for careful software engineering work. It helps coding agents inspect context, solve the real problem, avoid over-engineering, make minimal correct changes, and verify their work.

## Install

Install with the Skills CLI:

```bash
npx skills add tuoitho/careful-coding-skill --skill careful-coding
```

Install globally for a specific agent:

```bash
npx skills add tuoitho/careful-coding-skill --skill careful-coding -a claude-code -g -y
npx skills add tuoitho/careful-coding-skill --skill careful-coding -a codex -g -y
npx skills add tuoitho/careful-coding-skill --skill careful-coding -a gemini-cli -g -y
npx skills add tuoitho/careful-coding-skill --skill careful-coding -a opencode -g -y
```

Install globally for all detected agents:

```bash
npx skills add tuoitho/careful-coding-skill --skill careful-coding --agent '*' -g -y
```

List available skills from this repository:

```bash
npx skills add tuoitho/careful-coding-skill --list
```

## Skill

### careful-coding

Use when handling software engineering tasks such as coding, debugging, refactoring, architecture, testing, documentation, code review, or technical decision-making.

The skill focuses on:

- understanding the real goal before acting
- inspecting relevant code and project conventions
- making the smallest correct change
- avoiding speculative abstractions and unnecessary dependencies
- considering practical edge cases and risks
- verifying with targeted tests, builds, type checks, or manual reproduction

## Repository Structure

```text
skills/
  careful-coding/
    SKILL.md
```

## Compatibility

This skill follows the Agent Skills format and does not rely on agent-specific hooks or tool permissions. It can be installed by agents supported by the `skills` CLI, including OpenCode, Claude Code, Codex, Gemini CLI, Cursor, GitHub Copilot, Cline, Windsurf, and others.

Common global install locations managed by the `skills` CLI:

| Agent | CLI value | Global path |
| --- | --- | --- |
| Claude Code | `claude-code` | `~/.claude/skills/` |
| OpenCode | `opencode` | `~/.config/opencode/skills/` |
| Codex | `codex` | `~/.codex/skills/` |
| Gemini CLI | `gemini-cli` | `~/.gemini/skills/` |
| GitHub Copilot | `github-copilot` | `~/.copilot/skills/` |

## Star History

<a href="https://www.star-history.com/?repos=tuoitho%2Fcareful-coding-skill&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=tuoitho/careful-coding-skill&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=tuoitho/careful-coding-skill&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=tuoitho/careful-coding-skill&type=date&legend=top-left" />
 </picture>
</a>

## License

MIT
