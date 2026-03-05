# neurodiverse-claude-skills

A set of Claude skills I built for myself as a neurodivergent person. If your brain works anything like mine, they might help you too.

## What This Is

A growing collection of custom Claude skills built around the friction points I encounter day to day, things like processing messy voice-to-text input, breaking down tasks, translating communication, or reducing cognitive load.

These were built by a neurodivergent engineering manager for personal use — not by a clinician or researcher. They are shared openly in case they are useful to others. They are not a substitute for professional support.

The skills are designed around specific friction points rather than diagnostic labels. If a skill solves a problem you recognise, it is probably useful to you regardless of how your brain is wired.

## Who These Are For

Anyone who finds that their brain creates friction around communication, task management, writing, or processing information. You do not need a diagnosis to find these useful.

## Skills

| Skill | What It Does | Friction It Addresses |
|-------|-------------|----------------------|
| [voice-input-processor](skills/voice-input-processor/SKILL.md) | Interprets messy, unstructured voice-to-text input, finds the intent, and reformats it for use | Unstructured speech input, non-linear thinking, word substitution errors |
| [brain-dump-organiser](skills/brain-dump-organiser/SKILL.md) | Takes everything on your mind and organises it into clear themes and structure with optional next steps | Overwhelm, scattered thinking, context switching, mixed thoughts |

*This table will grow as skills are added.*

## How to Install a Skill

### Claude.ai (web or desktop)
1. Download the skill folder you want from the `skills/` directory
2. Zip the folder
3. Go to **Settings > Features > Skills** and upload the zip file
4. Enable the skill from your skills library
5. Claude will automatically use it when relevant, or you can invoke it directly with `/skill-name`

### Claude Code (terminal)
1. Download the skill folder you want from the `skills/` directory
2. Copy the folder to `~/.claude/skills/` (personal, available across all projects) or `.claude/skills/` (project-specific)
3. Claude will automatically discover and use the skill when relevant, or you can invoke it directly with `/skill-name`

### Claude Code via plugin marketplace
1. Add the marketplace:
```
   /plugin marketplace add 8ix/neurodiverse-claude-skills
```
2. Open the plugin browser:
```
   /plugin
```
3. Select **Browse and install plugins** and install the skills you want

For more on how Claude skills work, see [Anthropic's skills documentation](https://docs.claude.com).

## Design Principles

These skills were designed with the following in mind:

- **Function over label** — skills target cognitive friction points, not diagnostic categories
- **Forgiving input** — all skills are designed to work with messy, fragmentary, or voice-to-text input
- **Voice preservation** — skills help you communicate what you actually mean, not make you sound like someone else
- **No masking** — the goal is reduced cognitive load, not performing neurotypicality
- **Composable** — skills are designed to work independently and alongside each other

## Status

This is a personal project, actively being built. Skills will be added incrementally. Contributions and feedback are welcome but this is not a formally maintained open source project.

## Disclaimer

These skills were built by a neurodivergent person for personal use. They are not clinically validated, professionally endorsed, or a substitute for workplace accommodations or professional support. Use them if they help. Ignore them if they don't.
