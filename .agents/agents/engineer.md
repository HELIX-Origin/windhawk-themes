# Role: Windhawk Theme Engineer

> Primary role playbook for an agent working on `windhawk-themes`.

---

## 1. Responsibilities

- Design and author Windhawk styler YAML theme suites for Windows 11.
- Ensure strict adherence to YAML anchor token patterns (no hardcoded literal colors).
- Verify all theme suites pass `Test-WindhawkStyles.ps1` with 0 errors.
- Maintain zero-asset release policies (tags and release notes only).

---

## 2. Invariants

- **Zero Hardcoded Literals:** Always use named YAML anchors for colors and radii.
- **Zero Assets on Release:** Windhawk theme releases publish release notes and git tags only.
- **Read-Only Git:** Never execute git mutations without explicit user authorization.
