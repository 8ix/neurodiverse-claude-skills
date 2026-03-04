# neurodiverse-claude-skills

A set of Claude skills I built for myself as a neurodivergent person. If your brain works anything like mine, they might help you too.

## What This Is

A growing collection of custom Claude skills built around four neurodivergent profiles: dyslexia, ADHD, autism, and dyspraxia.

These were built by a neurodivergent engineering manager for personal use — not by a clinician or researcher. They are shared openly in case they are useful to others. They are not a substitute for professional support.

Each skill targets a specific friction point — things like processing messy voice-to-text input, breaking down tasks, translating communication, or reducing cognitive load — rather than being tied to a single diagnosis. Many of the challenges these skills address overlap across multiple profiles.

## Who These Are For

Anyone who finds that their brain creates friction around communication, task management, writing, or processing information. You do not need a diagnosis to find these useful.

## Skills

| Skill | What It Does | Profiles It Helps With |
|-------|-------------|----------------------|
| dyslexia-input-processor | Interprets messy voice-to-text input and cleans it up for use | Dyslexia |

*This table will grow as skills are added.*

## How to Install a Skill

1. Download the skill folder you want from the `skills/` directory
2. Copy the folder to `~/.claude/skills/` (personal, available across all projects) or `.claude/skills/` (project-specific)
3. Claude will automatically discover and use the skill when relevant, or you can invoke it directly with `/skill-name`

For more on how Claude skills work, see [Anthropic's skills documentation](https://docs.claude.com).

## Design Principles

These skills were designed with the following in mind:

- **Function over label** — skills target cognitive friction points, not diagnostic categories
- **Forgiving input** — all skills are designed to work with messy, fragmentary, or voice-to-text input
- **Voice preservation** — skills aim to help you communicate what you actually mean, not make you sound more neurotypical
- **No masking** — the goal is reduced cognitive load, not performance of neurotypicality
- **Composable** — skills are designed to work independently and alongside each other

## Status

This is a personal project, actively being built. Skills will be added incrementally. Contributions and feedback are welcome but this is not a formally maintained open source project.

## Disclaimer

These skills were built by a neurodivergent person for personal use. They are not clinically validated, professionally endorsed, or a substitute for workplace accommodations or professional support. Use them if they help. Ignore them if they don't.