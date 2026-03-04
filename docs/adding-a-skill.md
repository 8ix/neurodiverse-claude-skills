# Adding a New Skill to the Repository

A repeatable checklist for adding each new skill as it is built. Follow these three steps every time.

---

## Step 1 — Add the Skill Folder

Place the skill folder inside `skills/`:

```
neurodiverse-claude-skills/
└── skills/
    └── [skill-name]/
        └── SKILL.md
```

The folder name must match the `name` field in the SKILL.md frontmatter exactly.
If the skill has supporting files (scripts, reference docs), they go inside the same folder alongside SKILL.md.

---

## Step 2 — Update the README

Add a new row to the skills table in `README.md`:

```markdown
| [skill-name] | [one line description of what it does] | [friction points it addresses] |
```

Example:
```markdown
| voice-input-processor | Interprets messy, unstructured voice-to-text input, finds the intent, and reformats it for use | Unstructured speech input, non-linear thinking, word substitution errors |
```

---

## Step 3 — Update marketplace.json

Append a new entry to the `plugins` array in `.claude-plugin/marketplace.json`:

```json
{
  "name": "[skill-name]",
  "description": "[one line description of what it does]",
  "source": {
    "source": "github",
    "repo": "andbert/neurodiverse-claude-skills"
  },
  "skills": ["./skills/[skill-name]"]
}
```

---

## Checklist

- [ ] Skill folder added to `skills/`
- [ ] SKILL.md is inside the folder with correct `name` in frontmatter
- [ ] README skills table updated
- [ ] `marketplace.json` plugins array updated
