# GTM Automation

Claude skills and agents for go-to-market and channel marketing professionals: brand partner managers and the partners who sell and deliver for them.

Published by [DemandVector](https://www.demandvector.com).

## Skills

| Skill | Purpose |
|---|---|
| [channel-content-review](skills/channel-content-review/SKILL.md) | Review, tag, brief or rewrite channel content by buying stage, intent weight, reader role, delivery owner and fit to the partner's positioning. |

## Agents

None yet. See [agents/](agents/).

## Install a skill

**Claude apps:** zip the skill folder (for example `skills/channel-content-review/`), open Settings, go to Capabilities, and upload the zip under Skills.

**Claude Code:** copy the skill folder into `~/.claude/skills/`, so the file sits at `~/.claude/skills/channel-content-review/SKILL.md`.

## Layout

```
skills/
  <skill-name>/
    SKILL.md
agents/
  <agent-name>.md
```

Each skill is one folder with a `SKILL.md`. Each agent is one markdown file.
