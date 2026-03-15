# Cowork Skills

Community skill marketplace for [Cowork](https://github.com/selfsupervised-ai/agent-cowork) — the open-source desktop AI assistant.

## Browse Skills

Skills are listed in [`registry.json`](registry.json) and can be installed directly from the Cowork app via the Skills tab in the agent editor.

| Skill | Description |
|-------|-------------|
| [Code Reviewer](skills/code-reviewer/) | Reviews code for bugs, style, and security |
| [Test Writer](skills/test-writer/) | Generates unit and integration tests |
| [Refactor Helper](skills/refactor-helper/) | Suggests and applies refactoring patterns |
| [Doc Generator](skills/doc-generator/) | Generates documentation from code |
| [Git Commit Helper](skills/git-commit-helper/) | Crafts conventional commit messages |

## Install a Skill

1. Open Cowork and go to the **Agent Editor**
2. Switch to the **Skills** tab
3. Browse or search the marketplace
4. Click **Install** on any skill

Skills are downloaded to `.claude/skills/` in your project directory.

## Submit a Skill

See [CONTRIBUTING.md](CONTRIBUTING.md) for instructions on adding your own skills to this marketplace.

## License

MIT
