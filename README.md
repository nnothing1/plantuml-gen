# Claude Code Skills Repository

This repository contains custom skills for Claude Code.

## Available Skills

| Skill | Description |
|-------|-------------|
| [plantuml-gen](skills/plantuml-gen/) | Generate PlantUML diagrams for UML visualizations |

## Structure

```
skills-repo/
├── README.md
├── skills/
│   ├── plantuml-gen/
│   │   ├── SKILL.md
│   │   └── references/
│   └── ... (future skills)
```

## Adding a New Skill

1. Create a new directory with the skill name
2. Add `SKILL.md` with YAML frontmatter (name, description)
3. Optionally add `references/`, `scripts/`, or `assets/` directories

## Usage

Skills are automatically loaded by Claude Code when installed in `~/.claude/skills/`.