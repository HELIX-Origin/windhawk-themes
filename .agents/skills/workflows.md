# Workflows — windhawk-themes

> Authoritative development workflows and runbooks for `windhawk-themes`.

---

## 1. Creating a New Theme Suite

1. Create a new directory under `themes/<suite-name>/`.
2. Define the palette token anchors in `taskbar.yml` and `start.yml`.
3. Author the CSS-in-YAML styler rules mapped to Windhawk mod target classes.
4. Run validation:
   ```powershell
   pwsh -NoProfile -File tools/Test-WindhawkStyles.ps1
   ```
5. Capture a clean 16:9 screenshot and save as `preview.png`.

---

## 2. Modifying an Existing Style Definition

1. Locate the target YAML file in `themes/<suite-name>/`.
2. Update token anchor values or mod properties without breaking YAML syntax.
3. Verify all anchor references resolve cleanly.
4. Run the validation tool to confirm 0 errors.
