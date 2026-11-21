# Clean Tree Report

Source: `<SOURCE_REPO>`
Destination: `<CLEAN_TREE>`
Files: `219`

## Forbidden path hits
- none

## Forbidden content hits
- none

## Excluded
- `.git`, `.env`, `data/`, `logs/`, `.handoff/`, `.opencode/`, `.worktrees/`
- `ea/Reports/`, `ea/Config/*.ini`, binaries, caches, SARIF, runtime lockfiles
- internal agent docs, runbook, PRD/monetisation docs, unlicensed model weights

## Next
- Rotate credentials before any push.
- Create a fresh GitHub repo named `OpenAeterna` only after this report is clean.
