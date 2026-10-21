# windhawk-themes — Task Checklist & Workstream Tracking

> 📋 **Living Source of Truth**: Actionable task ledger for **windhawk-themes**.
> Statuses: ⬜ backlog · 🚧 in progress · ✅ done (tracked as `- [ ]` and `- [x]` checkboxes).
> High-level direction lives in [`ROADMAP.md`](./ROADMAP.md), active sprints in [`PLAN.md`](./PLAN.md), issues in [`BUGS.md`](./BUGS.md).

> [!IMPORTANT]
> AI agents are strictly required to update this page and related tracking ledgers **before** executing new feature work or bug fixes and keep them synchronized.

---

## 📜 Tracking Rules

- **No Typo Duplication**: When recording user reports, clean and fix all typos to preserve professional quality.
- **Consistent Formatting**: Maintain consistent formatting and style throughout all documentation to ensure readability and professionalism.
- **Clear Sectioning**: Use clear and descriptive headers for each section to improve navigation and readability.
- **Active Items First**: The currently active milestone, sprint, task, or workstream must always be placed at the top of the content sections.
- **Regular Updates**: Ensure that this file is regularly updated to reflect the latest developments and changes in the project.
- **Improve & Categorize User Directives**: Rewrite user directives into clean, self-contained engineering requirements grouped by domain sub-headers (e.g., **Architecture & Plugins**, **UI & Icons**, **Data & Cache**) so it is immediately clear what goes to what. Never dump raw chronological chat quotes or leave contradictory superseded statements.
- **100% Active Direction Accuracy**: Whenever a requirement pivots or supersedes an earlier decision, replace the superseded directive in place across `ROADMAP.md`, `PLAN.md`, `TODO.md`, and `BUGS.md`.
- **Same-Change Updates**: When a task changes behavior or scope, update this file **in the same change**.
- **Done Moves Down**: When a workstream is done, check it off and archive detailed checklists to `.github/TODO-ARCHIVE.md`, leaving a concise single-line summary under Completed Workstreams.
- **Explicit Project Tagging**: In multi-project or organization tracking ledgers, every workstream header, checklist group, and individual checkbox item MUST be explicitly prefixed with its project name and repository path (e.g., `[windhawk-themes] (windhawk-themes)` or `- [ ] [windhawk-themes] ...`) to prevent agent context confusion.
- **Tracking Docs Stay True**: Update `ROADMAP.md`, `TODO.md`, `BUGS.md`, and `PLAN.md` first or in lockstep with code changes.
- **Always Track Everything**: Every new feature request, enhancement, or bug report must be logged before execution.

---

## 🔥 Active Workstreams

### [windhawk-themes] Workstream W.01: Suite Polish & Multi-Mod Verification
- **Project Identifier:** `[windhawk-themes]`
- **Repository Path:** `windhawk-themes`
- **Target Component:** Core Architecture

**Locked user directives (normalized by domain):**
- **Start Menu:** Phone Link companion card flush with menu top; search box left edge flush with pinned apps card; companion toggle flush right.
- **Action Center:** Harmonize split-button toggle and chevron backgrounds (`SplitL2Button`); eliminate high-contrast blue fallback states.
- **Taskbar:** Theme internal snap containers (`SnapLayoutControl`, `LayoutBorder`) with Command Center glass without breaking layout bounds; restore frosted glass background and specular border to system tray overflow flyout.
- **Catalogue:** Theme Catalogue Integration — generate Jekyll showcase documentation in `docs/_catalogue/`.
- **Verification:** Full Multi-Mod Windows 11 Verification — validate cohesive visual language across 22H2, 23H2, and 24H2.

**Implementation checklist:**
- [ ] `[windhawk-themes]` **Start Menu Geometry** - Phone Link companion card flush with menu top; search box left edge flush with pinned apps card; companion toggle flush right.
- [ ] `[windhawk-themes]` **Action Center Quick Settings** - Harmonize split-button toggle and chevron backgrounds (`SplitL2Button`); eliminate high-contrast blue fallback states.
- [ ] `[windhawk-themes]` **Taskbar Snap Layout Containers** - Theme internal snap containers (`SnapLayoutControl`, `LayoutBorder`) with Command Center glass without breaking layout bounds.
- [ ] `[windhawk-themes]` **Taskbar Overflow Grid** - Restore frosted glass background and specular border to the system tray overflow flyout.
- [ ] `[windhawk-themes]` **Theme Catalogue Integration** - Generate Jekyll showcase documentation in `docs/_catalogue/`.
- [ ] `[windhawk-themes]` **Full Multi-Mod Windows 11 Verification** - Validate cohesive visual language across 22H2, 23H2, and 24H2.
- [ ] `[windhawk-themes]` **Validation & Verification** - run project quality gate with zero warnings.

---
- [ ] [windhawk-themes] **Theme Catalogue Integration** - Generate Jekyll showcase documentation in docs/_catalogue/.
- [ ] [windhawk-themes] **Full Multi-Mod Windows 11 Verification** - Validate cohesive visual language across 22H2, 23H2, and 24H2.

---

## ✅ Completed Workstreams & Archive

### ✅ [windhawk-themes] Workstream {{PREV_WORKSTREAM_ID}}: {{PREV_WORKSTREAM_TITLE}} ({{COMPLETED_DATE_OR_VERSION}})
- **Project Identifier:** `[windhawk-themes]`
- **Repository Path:** `windhawk-themes`

- [x] `[windhawk-themes]` {{COMPLETED_TASK_1}}
- [x] `[windhawk-themes]` {{COMPLETED_TASK_2}}
- [x] `[windhawk-themes]` {{COMPLETED_TASK_3}}

---

## 🔖 Metadata

- **Project**: windhawk-themes
- **Tracking Status**: {{STATUS_SUMMARY}}
