# Toolchain

Pinned CLI versions for my WSL machine, managed by [mise](https://mise.jdx.dev) and kept current by Renovate.

- `mise.toml` — the CLIs and their versions.
- `renovate.json` — update rules: new versions wait 3 days (majors 7 days plus dashboard approval); security fixes skip the wait; nothing auto-merges.

Apply after merging a PR:

```bash
git pull && mise install
```

Not tracked here: `git`, `make` (apt), `docker`, `pnpm` (Windows side), and `claude` (self-updates).
