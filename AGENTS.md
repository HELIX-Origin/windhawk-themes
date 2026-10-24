# windhawk-themes

Windhawk theming suites for Windows 11 — YAML style definitions targeting Windhawk styler mods (TaskbarXI, StartAllBack, ExplorerBlur, etc.).

## Verify

```powershell
pwsh -NoProfile -File tools/Test-WindhawkStyles.ps1
# Expected: 0 errors, all YAML definitions parse correctly
```

## Conventions

- Each suite is a self-contained directory under `themes/<suite-name>/`.
- Style definitions are YAML (`.yml`); CSS-in-YAML values follow the Windhawk styler schema.
- Uses `WindhawkBlur` and vertical gradient rim borders as primary visual motifs.
- Never hardcode hex colors outside the suite's token block at the top of each file.
- Releases: zero attached assets (git tag + release notes only); SemVer (`vMAJOR.MINOR.PATCH`).

## Invariants

MIT license, SemVer releases (zero-asset), zero-error YAML validation, community-health files.
See `CONTRIBUTING.md` and `.agents/rules/local-conventions.md` for full guidelines.
