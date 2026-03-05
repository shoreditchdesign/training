# Restore Single Codex Thread

This package contains one Codex conversation thread file:

- `_codex_sync/codex-home/sessions/2026/03/05/rollout-2026-03-05T01-42-37-019cbba9-4076-7963-aa32-ea6746c841a1.jsonl`

Thread first message:

- `Use the attached screenshot as a reference for you to scaffold out a detailed user flow diagram instruction...`

## On target machine

1. Pull latest repo changes.
2. Copy this file into your local Codex sessions path:

```bash
mkdir -p "$HOME/.codex/sessions/2026/03/05"
cp -a "$(pwd)/_codex_sync/codex-home/sessions/2026/03/05/rollout-2026-03-05T01-42-37-019cbba9-4076-7963-aa32-ea6746c841a1.jsonl" \
  "$HOME/.codex/sessions/2026/03/05/"
```

3. Restart Codex app.
