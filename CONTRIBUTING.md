# Contributing Skills

Thanks for contributing to the Cowork skill marketplace!

## How to Submit a Skill

1. **Fork** this repository
2. **Create a directory** under `skills/` with your skill's slug (lowercase, hyphenated):
   ```
   skills/your-skill-name/
   └── SKILL.md
   ```
3. **Write your SKILL.md** with YAML frontmatter:
   ```markdown
   ---
   name: Your Skill Name
   description: One-line description of what it does
   tags:
     - relevant
     - tags
   ---

   # Your Skill Name

   Detailed instructions for the AI assistant...
   ```
4. **Open a Pull Request** against `main`

## Skill Guidelines

- **One SKILL.md per directory** — the file must be named exactly `SKILL.md`
- **Frontmatter is required** — `name`, `description`, and `tags` fields
- **Be specific** — Write clear, actionable instructions, not vague goals
- **Include examples** — Show the AI what good output looks like
- **Keep it focused** — One skill should do one thing well
- **Test it** — Try your skill in Cowork before submitting

## Tags

Use existing tags when possible. Common tags:

`review`, `testing`, `quality`, `security`, `documentation`, `refactoring`,
`git`, `workflow`, `automation`, `api`, `patterns`, `developer-experience`

## What Happens After You PR

1. A maintainer reviews your skill for quality and clarity
2. On merge, a GitHub Action automatically updates `registry.json`
3. Your skill appears in the Cowork marketplace within minutes

## Additional Files

You can include additional files alongside SKILL.md (templates, examples, etc.):
```
skills/your-skill/
├── SKILL.md
├── templates/
│   └── example.md
└── examples/
    └── sample-output.md
```

All files in the directory are installed together when a user clicks Install.
