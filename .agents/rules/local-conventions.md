# Local Conventions — windhawk-themes

## Repository layout

- `themes/<suite-name>/` — one directory per theme suite.
- Inside each suite: one `.yml` style file per target mod (e.g. `taskbar.yml`, `start.yml`).
- `tools/` — PowerShell validation scripts (`Test-WindhawkStyles.ps1`).
- `docs/` — suite descriptions and screenshots (theme-neutral prose only; no theme token values in docs).

## YAML style file conventions

- Token block at the top: all hex colors, blur values, and spacing constants declared as named YAML anchors, then referenced via `*anchor` throughout the file. Never repeat a literal value.
- Every property block must include a comment explaining which Windhawk styler target it applies to.
- Use `WindhawkBlur` for all frosted-glass blur effects; use vertical gradient rim borders (`border-image: linear-gradient(...)`) for rim accents.
- CSS-in-YAML: follow the exact Windhawk styler property schema; never invent properties.

## Validation

```powershell
pwsh -NoProfile -File tools/Test-WindhawkStyles.ps1
# Must report: 0 errors. All YAML definitions parse correctly.
```

## Release policy

- Zero attached assets — git tag + release notes only.
- SemVer (`vMAJOR.MINOR.PATCH`); bump PATCH for style tweaks, MINOR for new suite additions.
- CHANGELOG.md entry required for every release.
