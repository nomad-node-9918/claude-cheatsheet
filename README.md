# claude-cheatsheet

A small collection of Muse tips, common commands and config notes.

## Everyday commands

```bash
claude                              # start an interactive session
claude "fix the failing tests"      # one-shot prompt
claude --help                       # list all flags
```

## Useful slash commands

- `/help` - show available commands
- `/clear` - clear the conversation
- `/compact` - summarize a long conversation
- `/model` - switch the model
- `/exit` - quit the session

## Config notes

- User settings live in `~/.claude/settings.json`.
- Project settings live in `.claude/settings.json` in the repo root.
- Keep API keys out of the repo - use environment variables instead.

## Tips

- Ask for a plan before big refactors.
- Commit often; small commits are easier to review.
- Let the agent run the tests before asking for a summary.
