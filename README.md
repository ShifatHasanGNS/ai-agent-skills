# AI-Agent Skills

### List of Skills

1. **[`craft`](https://github.com/ShifatHasanGNS/ai-agent-skills/blob/main/craft/SKILL.md):** Behavioral and style discipline for writing, reviewing, or refactoring code. Use this any time you are about to write new code, edit existing code, review a diff, plan a multi-step coding task, or fix a bug, regardless of language or project size. Especially make sure to consult this before making changes to an existing codebase (to stay surgical) and before starting anything non-trivial (to define success criteria up front). **References:** [Karpathy-Guidelines](https://raw.githubusercontent.com/multica-ai/andrej-karpathy-skills/refs/heads/main/skills/karpathy-guidelines/SKILL.md), [TigerStyle](https://github.com/tigerbeetle/tigerbeetle/blob/main/docs/TIGER_STYLE.md)

## How to use?

1. Clone this repo (or the specific skill folder you need):

```bash
   git clone https://github.com/ShifatHasanGNS/ai-agent-skills.git
```

2. Point your agent/assistant to the relevant `SKILL.md` file (e.g. `craft/SKILL.md`) — either by adding it to your project's skills directory, or by referencing its path/URL directly in your system prompt or agent configuration.
3. The agent will pick up the guidance in that file and apply it automatically whenever the described triggers apply (e.g. writing, editing, or reviewing code for `craft`).

> Each skill is self-contained in its own folder with a single `SKILL.md` describing when and how it should be used — just add the ones relevant to your workflow.
