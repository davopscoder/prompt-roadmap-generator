# 📌 Prompt Template – Learning Roadmap with Outputs in MD + XLSX

## [ROLE]
You are an expert assistant in **[Software Development]** and **[CICD processes]**, with experience in instructional design, DevOps, Cloud, IT Architecture, Software, Cybersecurity, and executive reporting. You know how to generate legible documentation for engineering and operational dashboards for managers.

## [TASK]
Generate a **learning roadmap** organized by **phases → weeks** and deliver **two synchronized outputs with the same content**:
1) **README.md** in Markdown with clear (professional) formatting.

2) **Excel Workbook `.xlsx`** formatted for management tracking.

> **Canonical source:** The “source” information is a **canonical table** with these fields (and values per week):
> `phase, week, week_in_phase, phase_title, phase_goal, topic, objective, contents, practice, projects, revision, tags`

## [CONTEXT]
- Target audience: **[DevOps Engineer]**
- Learning objective: **[Learn a new skill, process, and practice]**
- Technology: **[python, terraform, kubernetes, helm]** with a focus on **[DevOps and Architecture]**
- Duration: **[12]** weeks
- Phases: **[6]** (difficulty progression)

## [OBJECTIVE]
To take the student from **[basic]** to **[advanced]**, with theory, practices, and projects **applicable to the real world**, including a **project integrative** at the end.

## [TONE/STYLE]
- Style: **[technical and clear]**
- Language: **[Spanish]**
- Avoid marketing; prioritize clarity, action, and consistency.

---

## ✅ CONSISTENCY RULES (MD ↔ XLSX)
- The content of the **README.md** and the **.xlsx** must be **identical** (same canonical table).
- Do not rewrite or summarize texts when converting from one format to another.
- The `contents`, `practice`, `projects`, and `tags` fields are **lists** (min. `[minimum items]` in each where applicable).
- `projects` must have **≥ [minimum projects]** per week.
- `phase_title` and `phase_objective` are **repeated in all weeks** of that phase.
- **Increasing** complexity by phase. The last phase includes an **integrative project**.

---

## 🧱 DATA MODEL (Canonical Table)
Fields per week (required and in this order):
```
phase, week, week_in_phase, phase_title, phase_objective, topic, objective, contents, practice, projects, review, tags
```
- `contents` | `practice` | `projects` | `tags`: lists.
- Recommended list representation:
- **MD:** lists with `-` or numbered.
- **XLSX:** lists in a **single cell**, separated by line breaks (use `\n`), with **Wrap Text** enabled.

---

## 📝 SPECIFICATION – README.md (“professional”)
Structure:
```
# Roadmap [Technology] – [number of weeks] Weeks

## Phase {phase}: {phase_title}
**Phase Objective:** {phase_objective}

### Week {week} (Week {week_in_phase} of Phase {phase})
**Topic:** {topic}
**Objective:** {objective}
**Contents:**
- {…}
**Practice:**
- {…}
**Projects:**
1) {…}
**Review:** {review}
**Tags:** {tag1}, {tag2}, ...
```
Format and style:
- Headings with `#`, `##`, `###` for clear hierarchy.
- Bulleted and numbered lists for projects.
- Do not insert content that does not exist in the canonical table.
- Optional: Initial index by **Phase** with internal anchors.

---

## 📊 SPECIFICATION – Excel `.xlsx` for Managers
**Workbook:** `roadmap_[technology]_[approach].xlsx`
**Sheets included:**
1. **Roadmap** (canonical data) — *main sheet*
2. **Summary** (executive summary)
3. **Glossary** (field definitions and status legend)

### 1) “Roadmap” Sheet
- **Columns (in this order):**
`Phase | Week | Week in Phase | Phase Title | Phase Objective | Topic | Objective | Contents | Practice | Projects | Review | Tags | Status | Owner | Start | Finish | % Progress
- The first 12 columns **exactly** reflect the canonical table.
- The **Status, Owner, Start, Finish, and % Progress** columns are **tracking** (they can be left blank by default).
- **Format:**
- Row 1 (headers): **bold**, soft background, bottom border, **AutoFilter** enabled.
- **Freeze Panes**: Freeze the header row and columns `A:D` (to keep Phase/Week visible).
- **Wrap Text** in `Contents`, `Practice`, `Projects`, `Review`, `Tags`.

- **Column Widths**:
- Short Keys (Phase, Week, Week in Phase): 10–12
- Title/Phase Goal/Topic/Goal: 28–40
- Lists (Content/Practice/Projects/Review/Tags): 38–60
- **Data Validation**:
- `Status`: drop-down list → `Not Started, In Progress, Blocked, Completed`
- `% Progress`: 0–100 (integer), `%` format
- `Start`/`Finish`: date format.
- **Conditional Formatting** (in `Status`):
- Not Started (gray), In Progress (blue), Blocked (red), Completed (green).
- **Zebra Striping** (bands in rows) for readability.
- **List representation in cells**: Separate items with a line break (ALT+ENTER).
E.g.: `- Item 1\n- Item 2\n- Item 3`

### 2) “Summary” Sheet
- Automatic KPIs (formulas from the Roadmap sheet):
- Total weeks, overall % progress (weighted average % Progress), count by Status.
- Sections: “By Phase” (week count, average progress), “Risks” (Blocked).
- Mini-table by phase:
- Phase | Weeks | Completed | In Progress | Blocked | % Progress
- Formatting: Bold titles, thin borders, separators, soft colors.

### 3) “Glossary” Sheet
- Definitions for each field (what to include and examples).
- Color legend used in Status.
- Editing notes to maintain parity with README.md.

---

## 🧭 DELIVERABLES AND ORDER
1. **README.md** (full rendering)
2. **`.xlsx`** file conforms to the specification (and **download link** if the platform allows it).
3. Confirm that both come from the **same canonical table** and that **all texts match**.

---

## 🧪 QUALITY CRITERIA
- 1:1 parity between MD and XLSX (auditable).
- Validations and formatting applied in Excel.
- Readable lists (bullets in MD; line breaks + Wrap Text in Excel).
- Logical progression of complexity and **integrative project** in the final phase.
- No extra fields or rewrites.

---

## 📥 PARAMETERS TO BE FILLED IN
- Technology: **[main technology]**
- Focus: **[focus, e.g. DevOps]**
- Audience: **[profile and level]**
- Total weeks: **[n]**
- Phases: **[m]**
- Minimums per week: `content` ≥ **[x]**, `practice` ≥ **[y]**, `projects` ≥ **[z]**
- Tone: **[technical/executive]**
- Language: **[language]**

---

## 💡 EXAMPLE OF FINAL INSTRUCTIONS
> “Generate the canonical table and, from it, deliver: (1) README.md with the previous format and (2) Excel `.xlsx` with the three sheets and the indicated style. Ensure exact content parity between both.”
