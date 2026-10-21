# windhawk-themes — Active Sprint Planning

> 🎯 **Living Source of Truth**: Active sprint roadmap, execution architecture, and completed sprint history for **windhawk-themes**.
> Pair with [`ROADMAP.md`](./ROADMAP.md) (direction), [`TODO.md`](./TODO.md) (task ledger), and [`BUGS.md`](./BUGS.md) (known issues).

> [!IMPORTANT]
> AI agents are strictly required to update this page and related tracking ledgers **before** executing new feature work or bug fixes and keep them synchronized.

---

## 📜 Tracking Rules

- **No Typo Duplication**: When recording user reports, clean and fix all typos to preserve professional quality.
- **Consistent Formatting**: Maintain consistent formatting and style throughout all documentation to ensure readability and professionalism.
- **Clear Sectioning**: Use clear and descriptive headers for each section to improve navigation and readability.
- **Active Items First**: The currently active milestone, sprint, task, or workstream must always be placed at the top of the content sections.
- **Active Sprints Only in Top Section**: `## 🎯 Active Sprints` must contain ONLY the currently active sprint(s). Once a sprint is completed, move it immediately to `## ✅ Completed Sprints` (newest first).
- **Regular Updates**: Ensure that this file is regularly updated to reflect the latest developments and changes in the project.
- **100% Active Direction Accuracy**: Continuously refine and synchronize sprint tasks with the current active direction of each project; immediately update or remove superseded tasks rather than leaving contradictory statements.
- **Full History**: Every planned item from project history is represented under `## ✅ Completed Sprints`, newest first.
- **Explicit Project Tagging**: In multi-project or organization tracking ledgers, every sprint header, task, and execution deliverable MUST be explicitly prefixed with its current project name and repository path (e.g., `[windhawk-themes] (windhawk-themes)`) to prevent agent context confusion.
- **Tracking Docs Stay True**: Update `ROADMAP.md`, `TODO.md`, `BUGS.md`, and `PLAN.md` first or in lockstep with code changes.
- **Always Track Everything**: Every new feature request, enhancement, or bug report must be logged before execution.

---

## 🎯 Active Sprints

### 🚀 [windhawk-themes] (projects/windhawk-themes) — Milestone M.02b: Command Center Suite Polish & Geometry Alignment
- **Project Identifiers:** `[windhawk-themes]` (`projects/windhawk-themes`)
- **Target Objective:** Refine the proven Command Center Windows 11 styling suite (targeting `v0.2.0`) through precise geometry alignments, Quick Settings harmony, snap layout container theming, and tray overflow restoration, with the static gate (`tools/Test-WindhawkStyles.ps1`) holding 0 errors and 0 warnings.

#### 📝 Execution Tasks

1. **[windhawk-themes] (projects/windhawk-themes) Start Menu Geometry**:
   - `[windhawk-themes]` Phone Link companion card flush with menu top; search box left edge flush with pinned apps card; companion toggle flush right.
2. **[windhawk-themes] (projects/windhawk-themes) Action Center Quick Settings Harmony**:
   - `[windhawk-themes]` Harmonize split-button toggle and chevron backgrounds (`SplitL2Button`); eliminate high-contrast blue fallback states.
3. **[windhawk-themes] (projects/windhawk-themes) Taskbar Snap Layout Containers**:
   - `[windhawk-themes]` Theme internal snap containers (`SnapLayoutControl`, `LayoutBorder`) with Command Center glass without breaking layout bounds.
4. **[windhawk-themes] (projects/windhawk-themes) Taskbar Overflow Grid Restoration**:
   - `[windhawk-themes]` Restore frosted glass background and specular border to the system tray overflow flyout.

---

## 🔮 Planned Sprints

### ⏳ Sprint {{NEXT_SPRINT_ID}}: [windhawk-themes] (windhawk-themes) — {{NEXT_SPRINT_TITLE}}
- **Project Identifier:** `[windhawk-themes]`
- **Repository Path:** `windhawk-themes`
- `[windhawk-themes]` {{CANDIDATE_ITEM_1}}
- `[windhawk-themes]` {{CANDIDATE_ITEM_2}}

---

## ✅ Completed Sprints

### ✅ Sprint {{PREV_SPRINT_ID}}: [windhawk-themes] (windhawk-themes) — {{PREV_SPRINT_TITLE}} ({{COMPLETED_DATE_OR_VERSION}})
- **Project Identifier:** `[windhawk-themes]`
- **Repository Path:** `windhawk-themes`
- ✅ `[windhawk-themes]` {{COMPLETED_ACTION_1}}
- ✅ `[windhawk-themes]` {{COMPLETED_ACTION_2}}
- ✅ **Verification**: {{VERIFICATION_OUTCOME}}

---

## 🛠️ Verification Commands

```powershell
# Commands used to test and verify sprint changes
{{VERIFICATION_COMMANDS}}
```

---

## 🔖 Metadata

- **Project**: windhawk-themes
- **Tracking Mode**: {{SEMVER_OR_MILESTONES}}
