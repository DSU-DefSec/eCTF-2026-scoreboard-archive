# 2026 eCTF Scoreboard Archive

Static archive of the 2026 MITRE eCTF CTFd scoreboard from https://ectf.ctfd.io/

## Notes

- The CTFd theme assets (`themes/core/static/`) are vendored: the content-hashed files on `cdn.cloud.ctfd.io` are removed whenever the live instance upgrades CTFd, so the archive must not hot-link them.
- `404.html` uses `<base href="/eCTF-2026-scoreboard-archive/">` so it works at any depth. Update it if the repository is renamed or moved to a custom domain.
