# Verification Gate — windhawk-themes

> Authoritative verification gate for `windhawk-themes`.
> Run all validation commands from the repository root. All YAML style definitions must parse with 0 errors.

---

## Verification Commands

```powershell
# 1. Run PowerShell style and schema validator
pwsh -NoProfile -File tools/Test-WindhawkStyles.ps1

# 2. Strict YAML syntax and anchor validation
# All anchors must resolve cleanly; zero undefined anchors
```

---

## Quality Gate Invariants

- **0 Errors Required:** Validator script must report 0 syntax and schema errors.
- **Anchor Integrity:** All hex colors and dimensions must be defined via named YAML anchors at the top of the file; no duplicate unanchored literals.
- **Zero Assets on Release:** Release policy invariant — git tag and markdown release notes only; no binary assets attached.
