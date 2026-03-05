# Restore Codex Threads

This package contains two Codex conversation thread files:

- `_codex_sync/codex-home/sessions/2026/03/05/rollout-2026-03-05T01-42-37-019cbba9-4076-7963-aa32-ea6746c841a1.jsonl`
- `_codex_sync/codex-home/sessions/2026/03/05/rollout-2026-03-05T01-23-55-019cbb98-2165-7083-b0da-6ee18a95609c.jsonl`

Thread identifiers:

- `Use the attached screenshot as a reference for you to scaffold out a detailed user flow diagram instruction...`
- `Can you use the Figma MCP to get the design context of my templates and group them by site templates...`

## On target machine

1. Pull latest repo changes.
2. Copy these files into your local Codex sessions path:

```bash
mkdir -p "$HOME/.codex/sessions/2026/03/05"
cp -a "$(pwd)/_codex_sync/codex-home/sessions/2026/03/05/rollout-2026-03-05T01-42-37-019cbba9-4076-7963-aa32-ea6746c841a1.jsonl" "$HOME/.codex/sessions/2026/03/05/"
cp -a "$(pwd)/_codex_sync/codex-home/sessions/2026/03/05/rollout-2026-03-05T01-23-55-019cbb98-2165-7083-b0da-6ee18a95609c.jsonl" "$HOME/.codex/sessions/2026/03/05/"
```

3. Restart Codex app.
