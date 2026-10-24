# Architecture — windhawk-themes

> Authoritative architectural specification for `windhawk-themes`.
> Windhawk theming suites for Windows 11.

---

## 1. Directory Structure

```
windhawk-themes/
├── themes/                     # Theme suites
│   └── <suite-name>/           # Individual theme suite directory
│       ├── taskbar.yml         # Taskbar styler definitions
│       ├── start.yml           # Start menu styler definitions
│       ├── explorer.yml        # File Explorer blur and style overrides
│       └── preview.png         # Screenshot / preview asset
├── tools/                      # PowerShell validation tools
│   └── Test-WindhawkStyles.ps1 # YAML syntax and anchor linter
└── docs/                       # Suite documentation and guides
```

---

## 2. Token Architecture & CSS-in-YAML

- **Anchor Block:** Hex colors, dimensions, and blur scales are authored at the top of each file as YAML anchors (`&accent`, `&bg_blur`, `&rim_gradient`).
- **Target Mapping:** Windhawk mod selectors match specific UI elements in the Windows 11 desktop environment (`Taskbar`, `StartMenu`, `ExplorerFrame`).
- **Visual Palette:** Features frosted glass (`WindhawkBlur`), obsidian dark tones, and subtle vertical gradient borders.
