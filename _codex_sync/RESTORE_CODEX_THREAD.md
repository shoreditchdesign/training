# Restore Single Codex Thread

This package contains one Codex conversation thread file:

- `_codex_sync/codex-home/sessions/2026/02/26/rollout-2026-02-26T11-34-37-019c99ba-b9e9-73b2-94cd-43a72e3cad08.jsonl`

## On target machine

1. Pull latest repo changes.
2. Copy this file into your local Codex sessions path:

```bash
mkdir -p "$HOME/.codex/sessions/2026/02/26"
cp -a "$(pwd)/_codex_sync/codex-home/sessions/2026/02/26/rollout-2026-02-26T11-34-37-019c99ba-b9e9-73b2-94cd-43a72e3cad08.jsonl" \
  "$HOME/.codex/sessions/2026/02/26/"
```

3. Restart Codex app.

## Notes

- This is only one thread, not your full Codex state.
- If the same file exists on target machine, this copy will overwrite it.
